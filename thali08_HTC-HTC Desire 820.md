#### Test 506502789b39735_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  908): Waited long enough for: ServiceRecord{42f3a8a8 u0 com.htc.htclocationservice/.AutoSettingService}
,--------- beginning of /dev/log/main
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  908):    returned true
E/cutils-trace( 4346): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4346): ====startRecUseTime====
D/htc.customization.log.level( 4346):  is 
W/CustomizationLogLevel( 4346): Level value is invalid, use default level 2
D/CustomizationManager( 4346):  Read ACC file spent 0.066 (s)
D/CIDMapFileReader( 4346): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4346): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4346): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4346): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4346): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4346): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4346): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4346): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4346): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4346): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4346): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4346): Parsing tag category name = system
I/CustomizationCIDLoader( 4346): Parsing tag category name = application
I/CustomizationCIDLoader( 4346): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4346): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4346): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4346): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4346): Parsing tag category name = Settings
D/CustomizationManager( 4346):  Read CID file spent 0.107 (s)
D/CustomizationManager( 4346):  All configurations done spent 0.107 (s)
W/HtcNativeFlag( 4346): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4346): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4346): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4346): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  908): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  908): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4346
D/PMS     (  908): acquireHCC(425c1a30): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 908 1000 null
D/PMS     (  908): acquireHCC(425afa00): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 908 1000 null
I/Intent  (  908): @test_code: getHtcIntentFlag: 0 obj: 1130918432
D/PMS     (  908): acquireWL(4258afa8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 908 1000 null
I/FeedHostManager( 1275): [onPause]
I/FeedProviderManager( 1275): onPause
I/FeedHostManager( 1275): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@4221fe48
I/SocialFeedProvider( 1275): +onPause
I/SocialFeedProvider( 1275): -onPause
I/ActivityManager(  908): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4357 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1275): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4357): Binding Chromium to main looper Looper (main, tid 1) {41a95c18}
I/LibraryLoader( 4357): Expected native library version number "",actual native library version number ""
I/chromium( 4357): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4357): Initializing chromium process, renderers=0
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  908): java.lang.Throwable: stack dump
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@436e46a0:true
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  908): acquireWL(4252ba10): PARTIAL_WAKE_LOCK  AudioMix 0x1 374 1013 null
D/PMS     (  908): acquireWL(4252a5d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 374 1013 null
D/PMS     (  908): releaseWL(4252ba10): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4357): 1101709312: getState(). Returning 12
I/Adreno-EGL( 4357): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4357): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4357): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4357): Local Branch: 
I/Adreno-EGL( 4357): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4357): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4357):                  aa63bbd948f41d15fc72f585e
W/chromium( 4357): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4357): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4357): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4357): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4357): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4357): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4357): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4357): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4357): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4357): CordovaWebView is running on device made by: HTC
,W/AwContents( 4357): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  908): Disable input method client, pid=1275
W/ResourceType( 4357): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4357): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41add6b0, mServedView=org.apache.cordova.engine.SystemWebView{41aa3318 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 4357): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  908): Displayed com.test.thalitest/.MainActivity: +284ms
I/InputMethodManagerService(  908): Enable input method client, pid=4357
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  908): releaseWL(4258afa8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4357): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4357): JniHelper::setJavaVM(0x4156c048), pthread_self() = 1662606416
D/JX-Cordova( 4357): jxcore cordova android initializing
D/PMS     (  908): acquireWL(4244cee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=101735, Int=0
D/PMS     (  908): releaseWL(4244cee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
I/ClockThread( 1120): now=1450229640054 next=59946
,I/dalvikvm-heap( 4357): Grow heap (frag case) to 11.572MB for 96598-byte allocation
,I/dalvikvm-heap( 4357): Grow heap (frag case) to 11.634MB for 144892-byte allocation
,I/dalvikvm-heap( 4357): Grow heap (frag case) to 11.748MB for 217334-byte allocation
,I/dalvikvm-heap( 4357): Grow heap (frag case) to 11.923MB for 325996-byte allocation
,I/dalvikvm-heap( 4357): Grow heap (frag case) to 12.198MB for 488990-byte allocation
,I/dalvikvm-heap( 4357): Grow heap (frag case) to 13.213MB for 1100216-byte allocation
,I/dalvikvm-heap( 4357): Grow heap (frag case) to 14.118MB for 1650320-byte allocation
,D/PMS     (  908): acquireWL(424c6770): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
,D/PMS     (  908): releaseWL(424c6770): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  908): acquireWL(4214be20): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
,I/dalvikvm-heap( 4357): Grow heap (frag case) to 15.468MB for 2475476-byte allocation
D/PMS     (  908): releaseWL(4214be20): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  908): acquireWL(41bf0a80): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
,D/PMS     (  908): releaseWL(41bf0a80): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  908): acquireWL(42042c38): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
,D/PMS     (  908): releaseWL(42042c38): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/CpuWake (  908): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  908): <<release mCpuPerf_Freq wakelock
D/PMS     (  908): releaseHCC(425c1a30): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  908): releaseHCC(425afa00): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4357): Grow heap (frag case) to 17.577MB for 3713210-byte allocation
,W/jxcore-log( 4357): Initializing JXcore engine
,W/jxcore-log( 4357): JXcore engine is ready
,W/jxcore-log( 4357): Starting JXcore engine
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,W/jxcore-log( 4357): Platform android
W/jxcore-log( 4357): 
,W/jxcore-log( 4357): Process ARCH arm
W/jxcore-log( 4357): 
,I/ActivityManager(  908): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4405 uid=10077 gids={50077}
,D/PMS     (  908): acquireWL(420cd978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10077}
V/AlarmManager(  908): sending alarm PendingIntent{422c80d8: PendingIntentRecord{422dfb38 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450229641990, Int=60000
,D/PMS     (  908): releaseWL(420cd978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4405): SMSBackupAgentService started
,D/SMSBackup( 4405): Checking restore status
D/SMSBackup( 4405): Restore complete
,D/SMSBackup( 4405): cancelCheckAlarm
,D/SMSBackup( 4405): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  908): killProcessQuiet, pid=3615
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3615:com.htc.task/u0a70 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3615
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): releaseWL(4252a5d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4357): JXcore Cordova bridge is ready!
I/jxcore-log( 4357): 
,W/jxcore-log( 4357): JXcore engine is started
,I/chromium( 4357): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiDataStallTracker(  908): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  908): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  908): updateDataStallInfo: mDataStallTxRxSum={txSum=38 rxSum=29} preTxRxSum={txSum=37 rxSum=28}
D/WifiDataStallTracker(  908): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  908): onDataStallAlarm: tag=19378 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  908): startDataStallAlarm: tag=19379 delay=15s
D/PMS     (  908): acquireWL(424cf8a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{42505460: PendingIntentRecord{422e64c8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105483, Int=0
D/PMS     (  908): releaseWL(424cf8a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4357): Toggling radios to true
I/jxcore-log( 4357): 
,D/BluetoothAdapter( 4357): enable(): BT is already enabled..!
,D/WifiManager( 4357): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  908): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  908): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  908): Settings:Agentvalue: 2
W/Settings:Agent(  908): >> traceCallingStack()
W/Settings:Agent(  908): Process.myPid(): 908
W/Settings:Agent(  908): Process.myTid(): 1287
W/Settings:Agent(  908): Process.myUid(): 1000
W/Settings:Agent(  908): 
W/Settings:Agent(  908): 
W/System.err(  908): java.lang.Throwable: stack dump
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  908): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  908): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  908): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  908): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  908): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  908): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  908): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  908): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
,W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  908): 
W/Settings:Agent(  908): << traceCallingStack(): 1(ms)
D/WifiManager( 4357): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  908): doBoolean: DISCONNECT
D/WifiManager( 4357): reconnect: Base Package Name=com.test.thalitest, uid=10348
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1137): TDLS: Tear down peers
I/wpa_supplicant( 1137): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4357): Radios toggled
I/jxcore-log( 4357): 
,D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  908): setWifiEnabled: true pid=4357, uid=10348
E/WifiService(  908): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  908): New client listening to asynchronous messages
I/WifiService(  908): isSprintWifiRestricted(): false
I/WifiService(  908): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  908): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4357): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4357): 
I/jxcore-log( 4357): Perf Test app loaded loaded
I/jxcore-log( 4357): 
I/Choreographer( 4357): Skipped 82 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4357): check test folder
I/jxcore-log( 4357): 
,I/jxcore-log( 4357): found test : ./testFindPeers.js
I/jxcore-log( 4357): 
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1137): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1137): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1137): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  908): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  908): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  908): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1137): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1137): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1137): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1137): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1137): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1137): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1137): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1137): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1137): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1137): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8122bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1137):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1137): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1137): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1137): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 1137): netlink: Operstate: linkmode=-1, operstate=5,
I/wpa_supplicant( 1137): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1137): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1137): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1137): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1137): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1137): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1137): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1137): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1137): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
D/Tethering(  908): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1137): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1137): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1137): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1137): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1137): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1137): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1137): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1137): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1137): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1137): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1137): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1137): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1137): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1137): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1137): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1137): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1137): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1137): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1137): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1137): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1137): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1137): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1137): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1137): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1137): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1137): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1137): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1137): nl80211: Event message available
D/wpa_supplicant( 1137): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1137): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  908):    returned true
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/WifiPerfLock(  908): release()
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
D/Tethering(  908): interfaceStatusChanged wlan0, false
D/WifiStateMachine(  908): PerfLock released for exiting ConnectedState
,D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
D/Tethering(  908): interfaceStatusChanged wlan0, false
,D/Tethering(  908): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1137): Power_Mode_Type mode = 0
I/wpa_supplicant( 1137): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1137): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  908):    returned true
D/DhcpStateMachine(  908): [RunningState] Stop DHCP
D/ConnectivityService(  908): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  908): acquireWL(43bfbee8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 908 1000 null
D/WifiP2pService(  908): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 4357): found test : ./testSendData.js
I/jxcore-log( 4357): 
D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  908): doBoolean: RECONNECT
D/libc    (  908): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1137): Fast associate: Old scan results
I/wpa_supplicant( 1137): wpa_supplicant_scan enter
I/wpa_supplicant( 1137): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1137): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1137): wpa_supplicant_trigger_scan +
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1137): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1137): nl80211: Event message available
D/wpa_supplicant( 1137): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  908):    returned true
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  908): Enter handleNetworkDisconnect
,D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1137): Power_Mode_Type mode = 0
I/wpa_supplicant( 1137): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 61
I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1891/10178)
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=19379 mDataStallAlarmIntent=PendingIntent{42336ee0: PendingIntentRecord{422e64c8 android broadcastIntent}}
,D/WifiNative-wlan0(  908):    returned true
,D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  908): Exit handleNetworkDisconnect
D/WifiP2pService(  908): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  908): Provision feature enable=false
D/ConnectivityService(  908): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/UsbnetStateTracker(  908): isAvailable+-
D/UsbnetStateTracker(  908): reconnect
,D/UsbnetStateTracker(  908): isAvailable+-
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WISPrService( 3804): >>>>>WISPrService start isConnected = false<<<<<
D/MDST    (  908): default: reconnect()
D/MDST    (  908): default: setTeardownRequested(false)
D/MDST    (  908): default: setEnableApn apnType =default , enable=true
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1891/10178)
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3804): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  908): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  908): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  908): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  908): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiService(  908): New client listening to asynchronous messages
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/WISPrService( 3804): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3804): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] entry_id:5   entry:0xb83c1190  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb83c12a0  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb83c1428  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb83c1860  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb83c0fd8  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb83c10f8  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): handleConnectivityChange: resetting
D/ConnectivityService(  908): resetConnections(wlan0, 3)
D/PMS     (  908): acquireWL(42300478): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1374 10028 null
D/ConnectivityService(  908): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  908): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  908): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/WirelessDisplayService(  908): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  908): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  908): startScan Pid: 908 Uid 1000
,D/WifiNative-wlan0(  908): doBoolean: SCAN
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1137): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiNative-wlan0(  908):    returned false
D/PMS     (  908): acquireWL(423b0bb8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  908): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/BatSI   (  908): WIFI scan started for: 650a0300 uid:1000
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/PMS     (  908): acquireWL(43fd48f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10028 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
,I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:2
D/PMS     (  908): releaseWL(43fd48f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  908): reportInetCondition for net -1, percentage: 0 by  (1374/10028)
D/PMS     (  908): releaseWL(423b0bb8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  908): releaseWL(42300478): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
,D/ConnectivityService(  908): mActiveDefaultNetwork: -1
,D/ConnectivityService(  908): handleInetConditionChange: no active default network - ignore
,I/chromium( 4357): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  908): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
,D/GpsLocationProvider(  908): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  908): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  908): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  908): ignore wifi update if we are not in OPENING or CLOSING
D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
D/CaptivePortalTracker(  908): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  908): NoActiveNetworkState
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(43488080): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): releaseWL(43488080): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1891/10178),
D/Tethering(  908): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,I/ConnectivityHelper( 1275): [onReceive] WIFI(1): DISCONNECTED,
V/Tethering(  908): bSetPropertyMultiRAB:false
I/NetworkMonitor( 3873): type=WIFI subType= reason=null isConnected=false
D/Tethering(  908): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  908): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  908): ipv4Default null
I/Tethering(  908): No IPv4 upstream interface, giving up.
D/Tethering(  908): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10075)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1443/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1931/1000)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.google.android.music (3873/10154)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4247/10100)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4247/10100)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (2450/10021)
I/ActivityManager(  908): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4428 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4428): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4428): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4428): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4428): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4428): Preparing secondary program dexes.
V/DexLibLoader( 4428): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4428): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
,V/DexLibLoader( 4428): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4428): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4428): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4428): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4428): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4428): Dex already copied
D/OdexVerifier( 4428): Odex verification is skipped.
,V/DexLibLoader( 4428): Creating class loader
,V/DexLibLoader( 4428): Finished creating class loader
V/DexLibLoader( 4428): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4428): Dex already copied
D/OdexVerifier( 4428): Odex verification is skipped.
,V/DexLibLoader( 4428): Creating class loader
,V/DexLibLoader( 4428): Finished creating class loader
V/DexLibLoader( 4428): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4428): Dex already copied
D/OdexVerifier( 4428): Odex verification is skipped.
,V/DexLibLoader( 4428): Creating class loader
,V/DexLibLoader( 4428): Finished creating class loader,
V/DexLibLoader( 4428): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4428): Dex already copied
D/OdexVerifier( 4428): Odex verification is skipped.
,V/DexLibLoader( 4428): Creating class loader
,V/DexLibLoader( 4428): Finished creating class loader
,V/DexLibLoader( 4428): Verifying classes from secondary dexes.
,D/DexLibLoader( 4428): DexLibLoader.ensureDexLoaded took 24 ms
,I/SensorManager(  908): mEventCount = 900
,W/dalvikvm( 4428): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4428): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4428): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4428): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4428): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4428): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4428): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4428): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4428): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1137): nl80211: Event message available
D/wpa_supplicant( 1137): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1137): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1137): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1137): nl80211: Survey data missing
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1137): Sorted scan results
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1137): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1137): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1137): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-78
I/wpa_supplicant( 1137): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
I/wpa_supplicant( 1137): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1137): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1137): Add randomness: count=8 entropy=0
D/wpa_supplicant( 1137): Add randomness: count=9 entropy=1
D/wpa_supplicant( 1137): Add randomness: count=10 entropy=2
D/wpa_supplicant( 1137): Add randomness: count=11 entropy=3
D/wpa_supplicant( 1137): Add randomness: count=12 entropy=4
D/wpa_supplicant( 1137): Add randomness: count=13 entropy=5
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1137): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1137): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1137): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1137): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1137): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1137): wpa_supplicant_pick_network+
I/wpa_supplicant( 1137): Selecting BSS from priority group 1
I/wpa_supplicant( 1137): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1137): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1137): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1137): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1137): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1137):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1137):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 1137): Start print parameters
I/wpa_supplicant( 1137): wpa_s->wpa_state is 3
I/wpa_supplicant( 1137): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1137): isConcurrentMode() is 0
I/wpa_supplicant( 1137): wpa_s->br_mirror_statu,s is 0
I/wpa_supplicant( 1137): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1137): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1137): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1137): wpa_s->reassociate is 1
I/wpa_supplicant( 1137): wpa_s->is_screen_on 1
I/wpa_supplicant( 1137): wpa_s->ifname wlan0
I/wpa_supplicant( 1137): End print parameters
I/wpa_supplicant( 1137): selected network = 2
D/wpa_supplicant( 1137): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb81244e8  current_ssid=0x0
D/wpa_supplicant( 1137): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1137): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1137): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1137): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1137): check if in concurrent case
I/wpa_supplicant( 1137): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  908): doString: LIST_DONGLES
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1137): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1137): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1137): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1137): RSN: PMKSA cache search - network_ctx=0xb81244e8 try_opportunistic=0
D/wpa_supplicant( 1137): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1137): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1137): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1137): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1137): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1137): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1137): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1137): nl80211: Unsubscribe mgmt frames handle 0xb8123718 (mode change)
D/wpa_supplicant( 1137): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8123718
D/wpa_supplicant( 1137): nl80211: Register frame type=0xd0 nl_handle=0xb8123718
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1137): nl80211: Register frame type=0xd0 nl_handle=0xb8123718
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1137): nl80211: Register frame type=0xd0 nl_handle=0xb8123718
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1137): nl80211: Register frame type=0xd0 nl_handle=0xb8123718
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1137): nl80211: Register frame type=0xd0 nl_handle=0xb8123718
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1137): nl80211: Register frame type=0xd0 nl_handle=0xb8123718
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1137): nl80211: Register frame type=0xd0 nl_handle=0xb8123718
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1137): nl80211: Register frame type=0xd0 nl_handle=0xb8123718
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1137): nl80211: Register frame type=0xd0 nl_handle=0xb8123718
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1137): nl80211: Register frame type=0xd0 nl_handle=0xb8123718
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1137): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1137):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1137):   * freq=2412
D/wpa_supplicant( 1137):   * Auth Type 0
D/wpa_supplicant( 1137):   * WPA Versions 0x2
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1137): nl80211: Connect request send successfully
D/wpa_supplicant( 1137): EAPOL: External noti,fication - EAP success=0
D/wpa_supplicant( 1137): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1137): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1137): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1137): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1137): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1137): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1137): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1137): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  908): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1137): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1137): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1137): reply (778) for get BSS: id=0
I/wpa_supplicant( 1137): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1137): freq=5220
I/wpa_supplicant( 1137): level=-51
I/wpa_supplicant( 1137): tsf=0000000108041411
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1137): ssid=NG7005g
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=1
I/wpa_supplicant( 1137): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1137): freq=2412
I/wpa_supplicant( 1137): level=-50
I/wpa_supplicant( 1137): tsf=0000000108041395
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1137): ssid=01ABC
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=2
I/wpa_supplicant( 1137): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1137): freq=2412
I/wpa_supplicant( 1137): level=-50
I/wpa_supplicant( 1137): tsf=0000000108041406
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1137): ssid=NG700
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=3
I/wpa_supplicant( 1137): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1137): freq=2437
I/wpa_supplicant( 1137): level=-78
I/wpa_supplicant( 1137): tsf=0000000108041416
I/wpa_supplicant( 1137): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1137): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=4
I/wpa_supplicant( 1137): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1137): freq=2427
I/wpa_supplicant( 1137): level=-81
I/wpa_supplicant( 1137): tsf=0000000108041421
I/wpa_supplicant( 1137): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1137): ssid=Gonzos
I/wpa_supplicant( 1137): ====
I/wpa_supplicant( 1137): id=5
I/wpa_supplicant( 1137): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1137): freq=2437
I/wpa_supplicant( 1137): level=-90
I/wpa_supplicant( 1137): tsf=0000000108041424
I/wpa_supplicant( 1137): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1137): ssid=UPC4688432
I/wpa_supplicant( 1137): ####
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  908): getDiscoveryDongleList
D/WifiStateMachine(  908): == begin of scan result ==
,D/WifiStateMachine(  908): == (6) end of scan result ==
,D/WirelessDisplayService(  908): getDiscoveryDongleList
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/WifiStateMachine(  908): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 108041411, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 108041395, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 108041406, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -78, frequency: 2437, timestamp: 108041416, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 4: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2427, timestamp: 108041421, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 108041424, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): add 6 to mScanResults
D/BatSI   (  908): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  908): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,E/FbInjectorInitializer( 4428): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1137): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1137): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1137): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1137): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1137): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1137): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1137): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1137): nl80211: Event message available
D/wpa_supplicant( 1137): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1137): nl80211: Connect event
D/wpa_supplicant( 1137): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1137): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1137): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1137): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1137): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1137): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1137): Add randomness: count=14 entropy=6
I/wpa_supplicant( 1137): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1137): TDLS: Remove peers on association
D/wpa_supplicant( 1137): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1137): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1137): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1137): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1137): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1137): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1137): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1137): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1137): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1137): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1137): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1137): EAPOL: enable timer tick
D/wpa_supplicant( 1137): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1137): htc_wext_set_keepalive +
I/wpa_supplicant( 1137): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1137): getPrivFuncNum +	
I/wpa_supplicant( 1137): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1137): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1137): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1137): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1137): Get randomness: len=32 entropy=7
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/Tethering(  908): interfaceStatusChanged wlan0, false
D/Tethering(  908): [isWifi] getHotspotEnabled: false
,D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/Tethering(  908): interfaceLinkStateChanged wlan0, true
D/WifiMonitor(  908): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  908): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  908): interfaceStatusChanged wlan0, true,
D/HTCRequest(  908): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  908): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  908): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  908): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  908): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700,
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  908): Enter handleAssociatedWithEvent
D/WifiStateMachine(  908): Associated
D/WifiStateMachine(  908): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  908): Exit handleAssociatedWithEvent
D/WifiStateMachine(  908): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  908): updateConnectedAP...,
D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WifiStateMachine(  908): WifiApDatabaseHandler, WiFi AP database Inserting ..,
D/WifiApDatabaseHandler(  908): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  908): This record is existed, only update it...
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1137): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiApDatabaseHandler(  908): updateConnectedAP...
D/wpa_supplicant( 1137): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb81239f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1137):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1137): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1137): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1137): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f35b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1137):    broadcast key
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 11
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1137): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,E/wpa_supplicant( 1137): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1137): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1137): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1137): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1137): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1137): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1137): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1137): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  908): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1137): set send_ind_to_ndc = 0
I/wpa_supplicant( 1137): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1137): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1137): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1137): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1137): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1137): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1137): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1137): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1137): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1137): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1137): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1137): EAPOL authentication completed successfully
I/wpa_supplicant( 1137): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 79
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1137): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1137): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1137): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  908): interfaceLinkStateChanged wlan0, true
,D/Tethering(  908): interfaceStatusChanged wlan0, true
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/Tethering(  908): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
,D/WifiApDatabaseHandler(  908): updateConnectedAP...,
,D/WifiStateMachine(  908): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  908): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  908): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  908): This record is existed, only update it...
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  908): Provision feature enable=false
D/ConnectivityService(  908): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3804): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3804): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,W/fb4a(:<default>):StaticBindingVerifier( 4428): Verify
,D/DhcpStateMachine(  908): [StoppedState] Start DHCP
D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1137): Power_Mode_Type mode = 1
I/wpa_supplicant( 1137): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiStateMachine(  908): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  908): acquireWL(42597760): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 908 1000 null
,D/WifiStateMachine(  908): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiNative-wlan0(  908):    returned null
E/WifiStateMachine(  908): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  908): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  908):    returned null
D/WifiP2pService(  908): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4246af00 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4246af00 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiService(  908): New client listening to asynchronous messages
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4428): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4428): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4428): Grow heap (frag case) to 9.518MB for 73240-byte allocation
,D/Process (  908): killProcessQuiet, pid=3241
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 3241:com.android.defcontainer/u0a19 (adj 15): empty #17
,D/PMS     (  908): acquireWL(4330b670): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2225 10028 null
,I/ActivityManager(  908): Recipient 3241
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(43ade678): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2225 10028 null
,D/PMS     (  908): releaseWL(4330b670): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,D/GCM     ( 1374): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
,D/PMS     (  908): releaseWL(43ade678): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,D/AutoSetting( 1422): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  908): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4457 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1422/10053)
,D/AutoSetting( 1422): Util - no network available!
,D/AutoSetting( 1422): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1422): service - mHandler: cancel location update
,D/AutoSetting( 1422): service -           changes count: 0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1422/10053)
,W/fb4a(:<default>):UserScope( 4428): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4428): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4428): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4457): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4457): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4457): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4457): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  908): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4471 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=3858
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 3858:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4457/10078)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4457/10078)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4457/10078)
,I/ActivityManager(  908): Recipient 3858
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4428): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  908): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4488 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=4191
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 4191:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4191
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  908): Client connection lost with reason: 4
,I/dalvikvm-heap( 4428): Grow heap (frag case) to 9.966MB for 84664-byte allocation
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4488): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4488): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4488): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4488): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4488): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/dalvikvm-heap( 4428): Grow heap (frag case) to 9.983MB for 28144-byte allocation
E/dalvikvm( 4428): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4428): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4428): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4428): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4428): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4428): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4428): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4428): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4428): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4428): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4428): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4428): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4428): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4428): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4428): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4428): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4428): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4428): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4428): Grow heap (frag case) to 10.028MB for 39954-byte allocation
,I/dalvikvm-heap( 4428): Grow heap (frag case) to 10.103MB for 79892-byte allocation
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4488/10151)
,V/WebViewChromiumFactoryProvider( 4488): Binding Chromium to main looper Looper (main, tid 1) {41a9b1d8}
,I/LibraryLoader( 4488): Expected native library version number "",actual native library version number ""
,I/chromium( 4488): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4488): Initializing chromium process, renderers=0
,D/PMS     (  908): acquireWL(43014640): PARTIAL_WAKE_LOCK  AudioMix 0x1 374 1013 null
,D/PMS     (  908): acquireWL(430b5cb0): PARTIAL_WAKE_LOCK  AudioMix 0x1 374 1013 null
,E/AudioManagerAndroid( 4488): BLUETOOTH permission is missing!
D/PMS     (  908): releaseWL(43014640): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4488): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4488): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4488): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4488): Local Branch: 
I/Adreno-EGL( 4488): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4488): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4488):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4488): Starting up...
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4488/10151)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4488/10151)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (4131/10160)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (4131/10160)
,D/Process (  908): killProcessQuiet, pid=3985
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 3985:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1891/10178)
,I/dalvikvm-heap( 4428): Grow heap (frag case) to 10.289MB for 75760-byte allocation
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1891/10178)
,D/GCM     ( 1374): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
,W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43ecaa00 u0 ReceiverList{43eca900 4428 com.facebook.katana/10026/u0 remote:43ba73e0}}
,W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43ecaa00 u0 ReceiverList{43eca900 4428 com.facebook.katana/10026/u0 remote:43ba73e0}}
,W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{424bf3f0 u0 ReceiverList{424bf390 4428 com.facebook.katana/10026/u0 remote:4203b3a8}}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
,D/PMS     (  908): acquireWL(42fca2c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1443 10028 null
,D/PMS     (  908): releaseWL(42fca2c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1443): Unknown pending intent to remove.
D/PMS     (  908): acquireWL(43bb03c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1443 10028 null
D/PMS     (  908): releaseWL(43bb03c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  908): Recipient 3985
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4428): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4428): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/wpa_supplicant( 1137): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1137): EAPOL: disable timer tick
,D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1137): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1137): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  908):    returned true
,D/WifiStateMachine(  908): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  908): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  908): releaseWL(42597760): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): gateway: /192.168.1.1
,D/WifiNative-wlan0(  908): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1137): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  908): VerifyingLinkState enter
D/WifiStateMachine(  908): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  908): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  908): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1120): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  908): startDataStallAlarm: tag=19381 delay=15s
,I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  908): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiWatchdogStateMachine(  908): WAN detection
D/ConnectivityService(  908): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  908): Provision feature enable=false
D/ConnectivityService(  908): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  908): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  908): default: teardown()
D/MDST    (  908): default: setTeardownRequested(true)
D/MDST    (  908): default: setEnableApn apnType =default , enable=false
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1891/10178)
D/MDST    (  908): default: setTeardownRequested(true)
D/ConnectivityService(  908): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/WISPrService( 3804): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  908): syncGetConfiguredNetworks
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1120): WifiActivity: 3
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/ConnectivityService(  908): Unexpected mtu value: android.net.wifi.WifiStateTracker@423c8a68
D/ConnectivityService(  908): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  908): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  908): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  908): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  908): handleConnectivityChange: resetting
D/Nat464Xlat(  908): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  908): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  908): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  908): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  908): acquireWL(42cc3540): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
D/WirelessDisplayService(  908): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  908):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4457/10078)
,D/PMS     (  908): acquireWL(430e0e00): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2225 10028 null
,I/QuickSettingWifi( 1120): receive.wifiConnect:true wifiAPname:NG700 elapse:2
D/PMS     (  908): acquireWL(43253160): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2225 10028 null
D/PMS     (  908): releaseWL(430e0e00): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
I/logwrapper(  365): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2225): Preparing to send checkin request
,I/EventLogService( 2225): Accumulating logs since 1450229593589
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 2225): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2225): Using GMS GoogleHttpClient
,D/ConnectivityService(  908): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  908): getNetworkInfo networkType=9 called by com.google.android.gms (2225/10028)
,D/PMS     (  908): releaseWL(42cc3540): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.google.android.gms (2225/10028)
,W/GLSUser ( 1374): GoogleAccountDataService.getToken()
,W/GLSActivity( 1374): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1374): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1374): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1588): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
W/CheckinRequestBuilder( 2225): awaiting user notification for token
,D/DotMatrix( 1588): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41ac3ef8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 8 3 12
,I/ActivityManager(  908): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4563 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4563): install
,I/MultiDex( 4563): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4563): loading existing secondary dex files
,I/MultiDex( 4563): load found 1 secondary dex files
,I/MultiDex( 4563): install done
,I/ProviderInstaller( 4563): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1374): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/PMS     (  908): Going to sleep due to screen timeout...
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42146260
,I/ActivityManager(  908): mThumbnailWidth=360, mThumbnailHeight=640
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = CM36282 Light sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42146260, eanble = 0, strlen(mName) = 59
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422ee508
W/SensorService(  908): Listener[1] = com.htc.smartdim.sensor_eye@4250b388
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  908): Couldn't get kernel wake lock stats
V/LightsService(  908): setLight #2: color=#0
D/qdlights(  908): set_light_buttons_func: on=0 brightness=0
V/LightsService(  908): setLight #0: color=#0
,D/WirelessDisplayService(  908): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  908): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  908): mWirelessDisplayManager is null
,W/Settings( 4563): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (4563/10028)
,I/jxcore-log( 4357): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4357): 
,D/WIFI_ICON( 1120): WifiActivity: 0
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  908): releaseWL(43bfbee8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  908): NetTransition Wakelock for ConnectedState released by timeout
,D/SurfaceControl(  908): Excessive delay in blankDisplay() while turning screen off: 390ms
,V/KeyguardServiceDelegate(  908): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@425dce58)
D/NfcService( 1260): ScreenObserver: OFF
D/NfcService( 1260): applyRouting - 0
V/KeyguardServiceDelegate(  908): **** SHOWN CALLED ****
,D/NfcService( 1260): applyRouting -2
D/PMS     (  908): nativeSetInteractive:false
D/PMS     (  908): nativeSetInteractive:false done
D/PMS     (  908): nativeSetAutoSuspend:true
D/PMS     (  908): nativeSetAutoSuspend:true done
D/HABCtrl (  908): TPE algorithm. remove timeout.
D/PMS     (  908): OOBE c monitor 11
I/InputManager(  908): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  908): screenObserver, isScreenOn=false
I/InputMethodManagerService(  908): Disable input method client, pid=4357
D/PMN     (  908): wakingUp
D/PMS     (  908): acquireWL(422fcbd8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1260 1027 null
I/WindowManager(  908): No lock screen! windowToken=null
D/PMS     (  908): releaseWL(422fcbd8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,W/ResourceType( 4357): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4357): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41aa3318 VFEDH.C. .F...... 0,0-720,1134 #64}
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PMN     (  908): onScreenOn
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/PMS     (  908): acquireWL(42303230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
D/PMS     (  908): releaseWL(42303230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/AlarmManager(  908): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.musicenhancer (3896/10051)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
,D/CaptivePortalTracker(  908): NoActiveNetworkState
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1891/10178)
,V/Tethering(  908): bSetPropertyMultiRAB:false
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,I/ConnectivityHelper( 1275): [onReceive] WIFI(1): CONNECTED
,D/Tethering(  908): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  908): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  908): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  908): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  908): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  908): Found interface wlan0
,D/Tethering(  908): TetherMasterSM: InitialState processMessage what=3
,D/MtpService( 2450): [MTP][onReceive]+android.intent.action.USER_PRESENT
I/acms    ( 1931): Checking Certificates
I/acms    ( 1931): Checking Developer Certificates
I/acms    ( 1931): Checking Application Certificates
I/acms    ( 1931): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1931): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1931): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1931): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1931): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1931): Updating next query delay: 75600000
I/mlserverapp( 1931): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1931): cancelACMSProgrammedChecks
,D/MtpService( 2450): [MTP][onReceive]-
,D/NfcService( 1260): applyRouting - 0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10075)
D/PMS     (  908): acquireWL(42f6cd70): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1931/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1443/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4247/10100)
D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
I/IntentController( 1120): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1260): applyRouting -2
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,I/NetworkMonitor( 3873): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4457/10078)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(42046270): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1260 1027 null
D/PMS     (  908): releaseWL(42046270): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.google.android.music (3873/10154)
D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4247/10100)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(43182788): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/GpsLocationProvider(  908): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  908): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  908): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  908): ignore wifi update if we are not in OPENING or CLOSING
,D/WirelessDisplayService(  908): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(43182788): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  908): releaseWL(42f6cd70): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  908): startDataStallAlarm: tag=19382 delay=15s
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
D/ConnectivityService(  908): getActiveNetworkInfo called by  (2450/10021)
D/AlarmManager(  908): ACTION_SCREEN_ON
I/AlarmManager(  908): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done recovering
I/AlarmManager(  908): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done EPS screen off alarm recovering
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
I/ClockThread( 1120): stop update clock
,D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 1
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  908): BroadcastRSSIForIMS, newrssi =-50 , oldRssi= -200
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1137): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
D/PMS     (  908): acquireWL(4342eb40): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2225 10028 null
D/WIFI_ICON( 1120): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/PMS     (  908): releaseWL(4342eb40): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1374): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1137): SET_SCREEN_ON:On
I/wpa_supplicant( 1137): htc_wext_set_keepalive +
I/wpa_supplicant( 1137): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1137): getPrivFuncNum +	
I/wpa_supplicant( 1137): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1137): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1137): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1137): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1137): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  908):    returned true
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
,D/PMS     (  908): acquireWL(43598c30): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1374 10028 null
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/libc    ( 1374): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1374): [NET] getaddrinfo-,err=8
D/libc    ( 1374): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1374): [NET] getaddrinfo-, 1
D/libc    ( 1374): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =d4bb +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,V/SRS_Proc(  374): ParamSet string: screen_state=on
,D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1422): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/NetworkPolicy(  908): updateScreenOn: false
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1422/10053)
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/MobileConnectivityChangeReceiver( 4457): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4457): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1422): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1422): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1422): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1422): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1422/10053)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4488/10151)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (4131/10160)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (4131/10160)
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 221
D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1374): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1891/10178)
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/AutoSetting( 1422): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  908): acquireWL(4406c860): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1443 10028 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1862): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1862): onScreenOn: 1450229649378
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1862): onScreenOn: 1450229649378
,D/AutoSetting( 1422): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3804): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3804): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3804): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3804): Cust_ConnectToPC   : spcsc>false
D/        ( 3804): Cust_ConnectToPC   : IPT>true
D/        ( 3804): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3804): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3804): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3804): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3804): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3804): onReceive:android.intent.action.USER_PRESENT
D/PMS     (  908): releaseWL(4406c860): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/ContextImpl( 3804): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422ee508
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422ee508, eanble = 0, strlen(mName) = 91
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  908): Listener[0] = com.htc.smartdim.sensor_eye@4250b388
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  908): goingToSleep
,D/PMS     (  908): acquireWL(43f6d988): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 908 1000 null
I/SmartNS_PSService( 3804): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3804): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3804):  defaultType:0
,I/dalvikvm-heap( 4131): Grow heap (frag case) to 13.524MB for 1821008-byte allocation
,D/libc    ( 1374): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1374): [NET] getaddrinfo-,err=8
D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=19382 mDataStallAlarmIntent=PendingIntent{4256d778: PendingIntentRecord{422e64c8 android broadcastIntent}}
D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  908): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1137): SET_SCREEN_ON:Off
I/wpa_supplicant( 1137): htc_wext_set_keepalive +
I/wpa_supplicant( 1137): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1137): getPrivFuncNum +	
I/wpa_supplicant( 1137): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1137): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1137): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1137): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1137): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  908):    returned true
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,I/Adreno-EGL( 4563): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4563): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4563): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4563): Local Branch: 
I/Adreno-EGL( 4563): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4563): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4563):                  aa63bbd948f41d15fc72f585e
D/AlarmManager(  908): ACTION_SCREEN_OFF
I/AlarmManager(  908): [AlarmQueuing] screen off now: 
I/AlarmManager(  908): [AlarmQueuing] data connection: true
I/AlarmManager(  908): [AlarmQueuing] wifi connection: true
D/PMS     (  908): releaseWL(43f6d988): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
D/PMS     (  908): acquireWL(43c05fb0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 908 1000 null
D/PMS     (  908): acquireWL(43f20130): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10028 null
,V/SRS_Proc(  374): ParamSet string: screen_state=off
D/PMS     (  908): releaseWL(43f20130): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/NetworkPolicy(  908): updateScreenOn: false
,D/ContactMessageStore( 1248): start background delete task...
,D/wpa_supplicant( 1137): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  908):    returned true
D/ContactMessageStore( 1248): size: 0 , 0
,D/ContactMessageStore( 1248): Background delete complete
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(43c05fb0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4603 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=20 [5][1][0]
,I/Adreno-EGL( 4563): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4563): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4563): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4563): Local Branch: 
I/Adreno-EGL( 4563): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4563): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4563):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4563): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4563): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4563): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4563): Local Branch: 
I/Adreno-EGL( 4563): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4563): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4563):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
,D/AutoSetting( 1422): service - mHandler: cancel location update
,D/AutoSetting( 1422): service -           changes count: 0
W/ContextImpl( 4603): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] getTotalRam: 1873 Mb
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1862): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1862): onScreenOff
D/PMS     (  908): acquireWL(434976f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1443 10028 null
D/PMS     (  908): acquireWL(436e5808): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4603 1000 null
,D/PMS     (  908): releaseWL(434976f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/SmartSyncUtils( 4603): isEpsOn(), nState = 0
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1862): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1862): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1862): onScreenOff
,D/PMS     (  908): releaseWL(436e5808): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/fb4a(:<default>):UserScope( 4428): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):UserScope( 4428): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
D/SmartSyncUtils( 4603): getMobilePolicyEnabled, result = true
,D/Process (  908): killProcessQuiet, pid=4217
,I/ActivityManager(  908): Killing 4217:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4603): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  908): Recipient 4217
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/SmartSyncUtils( 4603): isEpsOn(), nState = 0
D/SmartSyncUtils( 4603): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4603): isEpsOn(), nState = 0
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4250b388
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 1
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4250b388, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 0
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4250b388, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4250b388
D/WifiService(  908): New client listening to asynchronous messages
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  908): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42548328 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42548328 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  908): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  908): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  908): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  908): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  908): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  908): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  908): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  908): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  908): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  908): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  908): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  908): 	at dalvik.system.NativeStart.main(Native Method)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
,D/GCM     ( 1374): Connected
D/PMS     (  908): acquireWL(43ff3708): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1374 10028 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
D/PMS     (  908): releaseWL(43598c30): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1374/10028)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  908): handleInetConditionChange: starting a change hold
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
D/PMS     (  908): releaseWL(43ff3708): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  908): acquireWL(43f02810): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1374 10028 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1374/10028)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1374): Message class mpf
D/ConnectivityService(  908): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1374/10028)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  908): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
D/PMS     (  908): releaseWL(43f02810): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  908): acquireWL(431b7740): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10028 null
D/PMS     (  908): releaseWL(431b7740): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/CheckinTask( 2225): Sending checkin request (8886 bytes)
D/libc    ( 2225): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2225): [NET] getaddrinfo-,err=8
D/libc    ( 2225): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2225): [NET] getaddrinfo-, 1
,D/libc    ( 2225): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =65b5 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=84
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2225): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2225): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2225): [NET] getaddrinfo-,err=8
,E/fb4a(:<default>):LocalFbBroadcastManager( 4428): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
,D/libc    ( 4428): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
D/libc    ( 4428): [NET] getaddrinfo-,err=8
D/libc    ( 4428): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    ( 4428): [NET] getaddrinfo-, 1
D/libc    ( 4428): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =e450 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 13
D/libc    (  365): [NET]res_nsend:resplen=74
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4428): [NET] getaddrinfo_proxy-, success
,I/global  ( 4428): call createSocket() return a new socket.
D/libc    ( 4428): [NET] getaddrinfo+,hn 11(0x33312e31332e39),sn(),family 0,flags 4
,D/libc    ( 4428): [NET] getaddrinfo-, SUCCESS
,D/PMS     (  908): releaseWL(430b5cb0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  908): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=4 [25][1][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/libc    ( 4428): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4428): [NET] getaddrinfo-,err=8
,D/PMS     (  908): acquireWL(43adb620): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10028 null
,D/PMS     (  908): releaseWL(43adb620): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/dalvikvm-heap( 4428): Grow heap (frag case) to 11.008MB for 32784-byte allocation
,D/ConnectivityService(  908): getNetworkInfo networkType=9 called by com.google.android.gms (2225/10028)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.google.android.gms (2225/10028)
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [5][0][0]
,W/GLSUser ( 1374): GoogleAccountDataService.getToken()
,W/GLSActivity( 1374): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1374): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1374): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1588): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1588): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2225): awaiting user notification for token
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41e4ca90 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 0 12 3 12
,I/CheckinTask( 2225): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2225): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,D/PMS     (  908): acquireWL(43e92358): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4428 10026 null
,D/GCM     ( 1374): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  908): releaseWL(43253160): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
E/ActivityThread( 2225): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41d337c8 that was originally bound here
E/ActivityThread( 2225): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41d337c8 that was originally bound here
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
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
,I/GCM     ( 1374): GCM config loaded
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4428/10026)
,D/WifiStateMachine(  908): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  908): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =57a7 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  908): Find DNS Address www.htc.com/23.59.123.86
,I/global  ( 4428): I/O error closing connection
I/global  ( 4428): java.net.SocketException: Socket is closed
I/global  ( 4428): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4428): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4428): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4428): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4428): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4428): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4428): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4428): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4428): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4428): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4428): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4428): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4428): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4428): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4428): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4428): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4428): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4428): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4428): Removing a connection that never existed!
D/PMS     (  908): releaseWL(43e92358): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/GAV2    ( 4488): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  908): acquireWL(42bad438): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1443 10028 null
,D/PMS     (  908): acquireWL(4304d5a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1443 10028 null
,D/PMS     (  908): releaseWL(42bad438): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  908): releaseWL(4304d5a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/Process (  908): killProcessQuiet, pid=4247
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4247:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4247
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  908): killProcessQuiet, pid=4270
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4270:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4270
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  908): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  908): acquireWL(43ff4f60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(43ff4f60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1422): service - mHandler: update timezone
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1519): service - onCreate()
W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1588): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1588): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1519): service - mHandler: update timezone
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1519): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1519): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1588): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1588): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1120): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41e79e90 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.htc.htclocationservice 2 7 2 11
,D/PMS     (  908): acquireWL(4385d208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{424aca70: PendingIntentRecord{421098e0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140870, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{44024f18: PendingIntentRecord{42445818 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141354, Int=0
,D/AutoSetting( 1422): service - handleMessage() stop self
,D/AutoSetting( 1422): service - onDestroy() END
,D/AutoSetting( 1422): service - handleMessage() quit looper
,D/GpsLocationProvider(  908): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  908): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  908): acquireWL(4347f7e0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
D/PMS     (  908): acquireWL(431e2158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10028 null
D/PMS     (  908): releaseWL(4385d208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  908): releaseWL(431e2158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =5458 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=243
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo_proxy-, success
I/global  (  908): call createSocket() return a new socket.
D/libc    (  908): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  908): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  908): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  908): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  908):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  908): releaseWL(4347f7e0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  908): killProcessQuiet, pid=3896
,I/ActivityManager(  908): Killing 3896:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Recipient 3896
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{43fdf518 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  908): acquireWL(43f5d990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=161735, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43f5d990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(43fedad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43fedad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/Process (  908): killProcessQuiet, pid=4288
,I/ActivityManager(  908): Killing 4288:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/AutoSetting( 1519): service - handleMessage() quit looper
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Recipient 4288
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1248): switchBindHtcMsgCursor: null
,D/PMS     (  908): acquireWL(43fd3598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(43fd3598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(43f9cf60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=221736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43f9cf60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42b65bd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10026}
,V/AlarmManager(  908): sending alarm PendingIntent{44012d30: PendingIntentRecord{428f7a68 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229002, Int=0
,I/ActivityManager(  908): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4645 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  908): sending alarm PendingIntent{424b4248: PendingIntentRecord{423170b0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450229758178, Int=10800000
,D/PMS     (  908): releaseWL(42b65bd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.aurora (4645/10047)
,D/Process (  908): killProcessQuiet, pid=4304
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4304:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4304
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,D/PMS     (  908): acquireWL(44077ea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10026}
,V/AlarmManager(  908): sending alarm PendingIntent{434aa1e8: PendingIntentRecord{436d7e00 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=230972, Int=120000
,V/AlarmManager(  908): sending alarm PendingIntent{42cb65a8: PendingIntentRecord{428f7a68 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231160, Int=0
,D/PMS     (  908): releaseWL(44077ea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  908): acquireWL(44072de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(44072de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(440424c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(440424c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(43b27590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=281735, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43b27590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43afe558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): releaseWL(43afe558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(434b0fe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(434b0fe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4357): Connected to the server!
I/jxcore-log( 4357): 
,I/chromium( 4357): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/PMS     (  908): acquireWL(434ad4c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=341736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(434ad4c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  908): acquireWL(434a59e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  908): n_update end
D/PowerUI ( 1120): closing low battery warning: level=100
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,D/PMS     (  908): releaseWL(434a59e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1374): GoogleAccountDataService.getToken()
,W/GLSActivity( 1374): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1374): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1374): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1588): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1588): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,W/GLSActivity( 1374): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1374): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1374): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1374): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1374): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1374): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1374): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1374): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41ac3ef8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4093): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4093): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4093): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4093): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4093): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4093): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4093): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4093): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1120): com.google.android.gms 3 15 4 12
,D/libc    ( 4093): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4093): [NET] getaddrinfo-,err=8
D/libc    ( 4093): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4093): [NET] getaddrinfo-, 1
,D/libc    ( 4093): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =eeac +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 295
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4093): [NET] getaddrinfo_proxy-, success
I/global  ( 4093): call createSocket() return a new socket.
D/libc    ( 4093): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4093): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4093): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4093): [NET] getaddrinfo-,err=8
,D/PMS     (  908): acquireWL(421ee4c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(421ee4c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(424af528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=401736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(424af528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(422af908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(422af908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(434d8e08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41cf2390: PendingIntentRecord{424349a8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=425740, Int=0
,D/PMS     (  908): acquireWL(42fc1938): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 908 1000 null
,V/AlarmManager(  908): sending alarm PendingIntent{42975d28: PendingIntentRecord{438f5dd0 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1450229896425, Int=0
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(424b0110): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(434d8e08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=9 [149][14][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/PMS     (  908): acquireWL(424d2290): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 908 1000 WorkSource{10160}
,D/PMS     (  908): releaseWL(42fc1938): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  908): releaseWL(424b0110): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(422aef10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(422aef10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(43482468): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(43482468): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/dalvikvm-heap( 4131): Grow heap (frag case) to 15.223MB for 1821008-byte allocation
,W/Uploader( 2225): No account for auth token provided
,I/dalvikvm-heap( 4131): Grow heap (frag case) to 16.976MB for 1821008-byte allocation
D/libc    ( 2225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 2225): [NET] getaddrinfo-,err=8
D/libc    ( 2225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 2225): [NET] getaddrinfo-, 1
,D/libc    ( 2225): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =6b2c +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2225): [NET] getaddrinfo_proxy-, success
,I/global  ( 2225): call createSocket() return a new socket.
D/libc    ( 2225): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 2225): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(4406c2b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
D/PMS     (  908): releaseWL(424d2290): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
D/PMS     (  908): releaseWL(4406c2b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/libc    ( 2225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 2225): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,D/PMS     (  908): acquireWL(434cf040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(434cf040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42f6c978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41cf2390: PendingIntentRecord{424349a8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=455818, Int=0
,D/PMS     (  908): acquireWL(436ce250): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 908 1000 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): releaseWL(42f6c978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42bc77e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(436ce250): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  908): releaseWL(42bc77e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  908): acquireWL(42fc3810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=461736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42fc3810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  908): acquireWL(42357cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): releaseWL(42357cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(436b68a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(436b68a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(425116d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=521735, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(425116d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43fc67b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10026}
,V/AlarmManager(  908): sending alarm PendingIntent{43f1f718: PendingIntentRecord{436d7e00 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=531169, Int=300000
,D/PMS     (  908): releaseWL(43fc67b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  908): acquireWL(44025440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(44025440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(43f5aa90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43f5aa90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42fc67b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=581736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42fc67b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42baddf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42baddf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1248): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1248): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1248): sku_id=99
,D/ContactMessageStore( 1248): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1248): start background delete task...
D/ContactMessageStore( 1248): size: 0 , 0
,D/ContactMessageStore( 1248): Background delete complete
,D/PMS     (  908): acquireWL(4252c8a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=641735, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4252c8a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43f6e650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): releaseWL(43f6e650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(425bc3e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/PMS     (  908): releaseWL(425bc3e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(440192d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=701735, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(440192d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43ade088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43ade088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/Process (  908): killProcessQuiet, pid=4319
,I/ActivityManager(  908): Killing 4319:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Recipient 4319
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(424e04c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(424e04c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43307548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=761736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43307548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(425c38d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(425c38d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43b60f68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43b60f68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(425369c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=821736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(425369c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43b14700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43b14700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4348b6e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4348b6e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43489320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=881736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43489320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4347f988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4347f988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4406cf30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(4406cf30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,D/PMS     (  908): acquireWL(43f90a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{41d5aa78: PendingIntentRecord{423d3220 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785469, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{43369f88: PendingIntentRecord{424e4df0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450230041064, Int=1800000
,V/AlarmManager(  908): sending alarm PendingIntent{423b95b8: PendingIntentRecord{4251e380 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450230478559, Int=900000
,D/PMS     (  908): acquireWL(43afcf30): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2225 10028 null
,D/PMS     (  908): acquireWL(424303f8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2225 10028 null
D/ConnectivityService(  908): Done.
,D/ConnectivityService(  908): Setting timer for 720seconds
,D/PMS     (  908): releaseWL(43afcf30): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,W/ContextImpl( 4603): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4603): call getInstance()
,I/EventLogService( 2225): Aggregate from 1450229648205 (log), 1450228241016 (data)
,D/PMS     (  908): releaseWL(43f90a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PowerUsageList:PowerUsageHelper( 4603): MY_DEBUG = false
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): releaseWL(424303f8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): acquireWL(440782d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=941736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(440782d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(44074ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(44074ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(440747b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(440747b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(44072b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1001735, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(44072b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(44023c80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4231ce20: PendingIntentRecord{4268b8c0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450230549672, Int=0
,D/SmartSyncUtils( 4603): isEpsOn(), nState = 0
D/PMS     (  908): acquireWL(4400f190): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4603 1000 null
D/PMS     (  908): releaseWL(44023c80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4603): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4603): [updateNmRange] USERNIGHT_TIMESTART = 18, USERNIGHT_TIMEEND = 23, nStart = 18, nEnd = 23, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4603): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4603): SettingOnTime = 1450303200000, randomSettingOnTime = 1450299610000
,D/SmartSyncScreenOnOffTimeReceiver( 4603): SettingOffTime = 1450285200000, randomSettingOffTime = 1450287007000
,D/SmartSyncScreenOnOffTimeReceiver( 4603): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4603): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4603): bNightModeTurnOffOnce = false
,D/PMS     (  908): releaseWL(4400f190): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  908): acquireWL(43ff5238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10028}
,V/AlarmManager(  908): sending alarm PendingIntent{4257ce90: PendingIntentRecord{4244d6f0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1011485, Int=0
,D/PMS     (  908): acquireWL(43ff46f0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1374 10028 null
,D/PMS     (  908): releaseWL(43ff46f0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  908): releaseWL(43ff5238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  908): acquireWL(43fdfd00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10028 null
,D/PMS     (  908): releaseWL(43fdfd00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  908): acquireWL(43fc7ba8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1374 10028 null
,D/GCM     ( 1374): Message class mow
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1374/10028)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  908): handleInetConditionChange: starting a change hold
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
,D/PMS     (  908): releaseWL(43fc7ba8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  908): acquireWL(43fa8358): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10028 null
,D/PMS     (  908): releaseWL(43fa8358): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  908): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=19 [109][21][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(43f92e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/PMS     (  908): releaseWL(43f92e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43ee4ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43ee4ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43abd890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1061736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43abd890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43aae040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43aae040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43a39ee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43a39ee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(435ab918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1121736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(435ab918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(434ad4c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(434ad4c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4313c400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1181735, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4313c400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(431123f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(431123f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(425529e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(425529e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(422eccf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1241736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(422eccf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(41c1a020): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(41c1a020): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
,D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(41b40588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(41b40588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42fd9018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1301735, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42fd9018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42385608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42385608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  908): updateBatteryInfo
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PMS     (  908): runPSCheck
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(425031b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(425031b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(436e74c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1361736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(436e74c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4258c348): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4258c348): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(423f4bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1421736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(423f4bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(41dac760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(41dac760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(431a38c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(431a38c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(424e0860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1481736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(424e0860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43826e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(43826e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43636940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43636940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42460498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1541736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42460498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42340438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42340438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42425990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42425990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43fdfa30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1601736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43fdfa30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42597bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42597bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(424e2690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1661736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  908): releaseWL(424e2690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42124a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42124a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42486ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42486ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(41f33ce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1721736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(41f33ce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4242bb20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4242bb20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(422e1188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(422e1188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43288ac0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1781736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43288ac0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42389680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(42389680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): acquireWL(42cc1d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42cc1d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(425096b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1841736, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  908): Prepared write state in 53ms
,I/ProcessStatsService(  908): Prepared write state in 34ms
,D/PMS     (  908): releaseWL(425096b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  908): Pruning old procstats: /data/system/procstats/state-2015-12-15-15-43-36.bin
,D/PMS     (  908): acquireWL(433d2b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(433d2b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42457030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
,D/PMS     (  908): releaseWL(42457030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42d6b438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{420bee48: PendingIntentRecord{4208ae60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1901735, Int=0
,D/Process (  908): killProcessQuiet, pid=4093
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  908): killProcessQuiet, pid=4234
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 4093:com.android.vending/u0a73 (adj 15): empty for 1812s
,I/ActivityManager(  908): Killing 4234:com.htc.cs.dm/u0a98 (adj 15): empty for 1826s
I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42d6b438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
I/ActivityManager(  908): Recipient 4234
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 4093
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(42d8e5e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,D/Process (  908): killProcessQuiet, pid=4488
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  908): killProcessQuiet, pid=4471
I/ActivityManager(  908): Killing 4488:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1800s
V/AlarmManager(  908): sending alarm PendingIntent{41d5aa78: PendingIntentRecord{423d3220 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1660324, Int=0
,I/ActivityManager(  908): Killing 4471:com.android.chrome/u0a96 (adj 15): empty for 1800s
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  908): killProcessQuiet, pid=4457
,I/ActivityManager(  908): Killing 4457:com.google.android.setupwizard/u0a78 (adj 15): empty for 1800s
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  908): killProcessQuiet, pid=3873
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  908): killProcessQuiet, pid=4405
I/ActivityManager(  908): Killing 3873:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
,I/ActivityManager(  908): Killing 4405:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1807s
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  908): Recipient 4488
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
V/AlarmManager(  908): sending alarm PendingIntent{422eb690: PendingIntentRecord{4249eda0 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820525, Int=1800000
D/ConnectivityService(  908): Done.
D/PMS     (  908): acquireWL(4402dc30): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
D/ConnectivityService(  908): Setting timer for 720seconds
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 4457
V/AlarmManager(  908): sending alarm PendingIntent{430086d8: PendingIntentRecord{4244d6f0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1911587, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{423b95b8: PendingIntentRecord{4251e380 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450231378559, Int=900000
,I/ActivityManager(  908): Recipient 4471
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 4405
,D/PMS     (  908): releaseWL(4402dc30): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  908): acquireWL(4335d460): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1374 10028 null
,D/PMS     (  908): releaseWL(4335d460): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  908): acquireWL(43f99830): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10028 null
,D/PMS     (  908): releaseWL(43f99830): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/ContextImpl( 4603): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  908): releaseWL(42d8e5e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/GCM     ( 1374): Message class mow
D/PMS     (  908): acquireWL(42599478): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1374 10028 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1374/10028)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  908): handleInetConditionChange: starting a change hold
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1374/10028)
,D/PMS     (  908): releaseWL(42599478): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  908): acquireWL(425b0820): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10028 null
,D/PMS     (  908): releaseWL(425b0820): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3873
,D/MediaRouterService(  908): Client com.google.android.music (pid 3873): Died!
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,TIME-OUT KILL (timeout was 1800000ms),D/ConnectivityService(  908): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=10 [166][17][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1137): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1137): nl80211: survey data missing!
E/wpa_supplicant( 1137): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1137): environment dirty rate=0 [0][0][0]
D/CustomizationManager( 4723): ====startRecUseTime====
D/htc.customization.log.level( 4723):  is 
W/CustomizationLogLevel( 4723): Level value is invalid, use default level 2
D/CustomizationManager( 4723):  Read ACC file spent 0.092 (s)
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4723): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4723): Parsing tag category name = system
I/CustomizationCIDLoader( 4723): Parsing tag category name = application
I/CustomizationCIDLoader( 4723): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4723): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4723): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4723): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4723): Parsing tag category name = Settings
D/CustomizationManager( 4723):  Read CID file spent 0.141 (s)
D/CustomizationManager( 4723):  All configurations done spent 0.141 (s)
W/HtcNativeFlag( 4723): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4723): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4723): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4723): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  908): deletePackageAsUser: pkg=com.test.thalitest, pid=4723, uid=2000 user=0
D/Process (  908): killProcessQuiet, pid=4357
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
I/ActivityManager(  908): Killing 4357:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  908): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  908):   Force finishing activity ActivityRecord{41c8ef20 u0 com.test.thalitest/.MainActivity t2}
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/InputDispatcher(  908): channel '4237ffc8 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  908): channel '4237ffc8 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
D/WifiService(  908): Client connection lost with reason: 4
W/InputDispatcher(  908): Attempted to unregister already unregistered input channel '4237ffc8 com.test.thalitest.MainActivity (s)'
I/WindowState(  908): WIN DEATH: Window{4237ffc8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/WindowManager(  908): WINDOW DIED Window{4237ffc8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/InputMethodManagerService(  908): Got RemoteException sending setActive(false) notification to pid 4357 uid 10348
W/Binder  ( 1210): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1210): java.lang.NullPointerException
W/Binder  ( 1210): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1210): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1210): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1210): 	at dalvik.system.NativeStart.run(Native Method)
W/PackageSettings(  908): Skipping PackageSetting{42232c60 com.example.hello/10356} due to missing metadata
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/acms    ( 1931): Unregistering com.test.thalitest
E/acms    ( 1931): Could not unregister removed application com.test.thalitest
D/DotMatrix( 1588): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1588): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1588): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  908): acquireWL(432d5ce8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1443 10028 null
W/GeofencerStateMachine( 1443): Ignoring removeGeofence because network location is disabled.
D/PMS     (  908): releaseWL(432d5ce8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/VoicemailCleanupService( 1289): Cleaning up data for package: com.test.thalitest
I/Launcher( 1275): Deferring update until onResume
D/Launcher( 1275): waitUntilResume // bindAppsRemoved
W/SystemReader( 1260): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
E/cutils-trace( 4723): Error opening trace file: No such file or directory (2)
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
D/PackageBroadcastService( 2225): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/ActivityManager(  908): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4739 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
E/ExternalAccountType( 1332): Unsupported attribute readOnly
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
D/PhoneApp( 1248): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4739): install
I/MultiDex( 4739): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4739): loading existing secondary dex files
I/MultiDex( 4739): load found 1 secondary dex files
I/MultiDex( 4739): install done
I/ActivityManager(  908): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4755 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PeopleContactsSync( 2225): CP2 sync disabled
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2225, uid=10028, userID:0
I/Icing   ( 2225): doRemovePackageData com.test.thalitest
D/PMS     (  908): acquireWL(423b9e40): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
D/PMS     (  908): releaseWL(423b9e40): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ProviderInstaller( 4739): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/MultiDex( 4755): install
I/MultiDex( 4755): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  908): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4755): loading existing secondary dex files
I/MultiDex( 4755): load found 1 secondary dex files
I/MultiDex( 4755): install done
I/ProviderInstaller( 4755): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
E/SQLiteDatabase( 2225): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 2225): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2225): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2225): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2225): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2225): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2225): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2225): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2225): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2225): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2225): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2225): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 2225): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 2225): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 2225): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 2225): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 2225): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2225): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2225): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2225): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 2225): Runtime exception while performing operation
E/ClearPendingStateOp( 2225): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 2225): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 2225): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 2225): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 2225): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 2225): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 2225): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 2225): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 2225): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 2225): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 2225): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 2225): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 2225): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 2225): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 2225): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 2225): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 2225): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 2225): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 2225): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 2225): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 2225): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 2225): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 2225): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 2225): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 2225): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 2225): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  908): Resuming delayed broadcast
E/SharedPreferencesImpl( 1210): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/[PluginManager]RegisterService( 1422): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/DropBoxManagerService(  908): Can't write: system_app_wtf
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
E/SQLiteLog( 1422): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1422): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c8629a8
W/[PluginManager]RegisterService( 1422): provider may killed!
W/[PluginManager]RegisterService( 1422): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1422): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1422): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1422): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1422): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1422): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1422): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1422): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1422): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1422): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1422): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1422): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1422): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1422): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1422): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1422): handle notify Blinkfeed plugin client changed
I/ActivityManager(  908): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4778 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
D/Process (  908): killProcessQuiet, pid=3804
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3804:com.android.settings/1000 (adj 15): empty for 1802s
E/SQLiteDatabase( 4739): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4739): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4739): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4739): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4739): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4739): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4739): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4739): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4739): threadid=12: thread exiting with uncaught exception (group=0x41664e30)
I/ActivityManager(  908): Recipient 3804
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  908): Client connection lost with reason: 4
E/AndroidRuntime( 4739): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4739): Process: com.google.android.gms.drive, PID: 4739
E/AndroidRuntime( 4739): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4739): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4739): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4739): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4739): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4739): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4739): 	at ctn.run(SourceFile:985)
E/ActivityManager(  908): App crashed! Process: com.google.android.gms.drive
D/Process ( 4739): killProcess, pid=4739
D/Process ( 4739): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
I/ActivityManager(  908): Recipient 4739
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.google.android.gms.drive (pid 4739) has died.
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4778, uid=10073, userID:0
D/Finsky  ( 4778): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (4778/10073)
D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (4778/10073)
D/Finsky  ( 4778): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/Settings( 4778): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4778): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4778): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4778): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4778): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4778): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4778): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4778): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4778): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4778): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4778): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4778): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4778): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4778): threadid=25: thread exiting with uncaught exception (group=0x41664e30)
E/ActivityManager(  908): App crashed! Process: com.android.vending
E/AndroidRuntime( 4778): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4778): Process: com.android.vending, PID: 4778
E/AndroidRuntime( 4778): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4778): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4778): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4778): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4778): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4778): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4778): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4778): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4778): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4778): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4778): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4778): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4778): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4778): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4778): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4778): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4778, uid=10073, userID:0
D/Process ( 4778): killProcess, pid=4778
D/Process ( 4778): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
D/Prism.PackageStateRece_( 1275): action: android.intent.action.PACKAGE_REMOVED
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
I/ActivityManager(  908): Recipient 4778
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/IcingCorporaProvider( 2897): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  908): Process com.android.vending (pid 4778) has died.
I/TrimMemoryManager( 1275): [trimMemory] 5
I/ActivityManager(  908): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4813 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2897): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2897): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63cf35c0
W/dalvikvm( 2897): threadid=15: thread exiting with uncaught exception (group=0x41664e30)
E/ActivityManager(  908): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2897): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2897): Process: com.google.android.googlequicksearchbox:search, PID: 2897
E/AndroidRuntime( 2897): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2897): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2897): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2897): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2897): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2897): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2897): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2897): 	at cid.d(PG:186)
E/AndroidRuntime( 2897): 	at clo.g(PG:594)
E/AndroidRuntime( 2897): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2897): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2897): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2897): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2897): 	at clr.tL(PG:827)
E/AndroidRuntime( 2897): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2897): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2897): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2897): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2897): killProcess, pid=2897
W/PackageManager(  908): Unable to load service info ResolveInfo{425b0ad8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  908): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  908): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  908): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  908): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  908): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  908): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 2897): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41b29f10 +
I/Prism.WidgetManager( 1275): onLoadItems() +
I/ActivityManager(  908): Recipient 2897
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  908): Client com.google.android.googlequicksearchbox (pid 2897): Died!
D/WifiService(  908): Client connection lost with reason: 4
I/ActivityManager(  908): Process com.google.android.googlequicksearchbox:search (pid 2897) has died.
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10998ms
D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  908): start
E/SQLiteDatabase( 4813): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4813): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4813): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4813): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4813): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4813): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4813): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4813): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4813): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4813): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4813): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4813): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4813): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4813): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4813): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4813): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4813): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4813): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4813): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4813): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4813): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4813): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4813): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4813): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4813): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4813): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4813): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4813): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4813): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4813): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4813): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4813): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4813): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4813): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4813): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4813): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4813): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4813): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4813): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4813): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4813): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4813): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4813): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4813): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4813): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4813): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4813): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4813): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4813): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4813): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4813): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4813): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4813): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4813): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4813): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4813): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4813): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4813): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4813): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4813): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4813): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4813): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4813): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4813): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4813): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4813): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4813): threadid=11: thread exiting with uncaught exception (group=0x41664e30)
E/ActivityManager(  908): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4813): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4813): Process: com.google.android.apps.docs, PID: 4813
E/AndroidRuntime( 4813): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4813): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4813): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4813): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4813): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4813): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4813): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4813): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
E/SQLiteDatabase( 4813): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4813): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4813): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4813): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4813): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4813): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4813): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4813): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4813): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4813): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4813): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4813): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4813): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4813): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4813): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4813): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4813): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4813): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4813): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4813): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4813): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4813): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4813): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4813): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4813): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4813): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4813): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4813): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4813): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4813): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4813): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4813): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4813): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4813): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4813): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4813): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4813): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4813): Opened ClientFlag.db in read-only mode
D/Process ( 4813): killProcess, pid=4813
D/Process ( 4813): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  908): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4829 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  908): Recipient 4813
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0

```
