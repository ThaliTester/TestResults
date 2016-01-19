#### Test 5644966031ce140_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  904): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4486 uid=10078 gids={50078}
D/PMS     (  904): acquireWL(43370098): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10078}
V/AlarmManager(  904): sending alarm PendingIntent{42542360: PendingIntentRecord{425f51f8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453204979974, Int=60000
D/PMS     (  904): releaseWL(43370098): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
D/PMS     (  904): acquireWL(425e2ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
--------- beginning of /dev/log/main
I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  904): sending alarm PendingIntent{42107ed8: PendingIntentRecord{41bb4ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=100612, Int=0
D/PMS     (  904): releaseWL(425e2ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SMSBackup( 4486): SMSBackupAgentService started
I/ClockThread( 1113): now=1453204980057 next=59943
D/SMSBackup( 4486): Checking restore status
D/SMSBackup( 4486): Restore complete
D/SMSBackup( 4486): cancelCheckAlarm
D/SMSBackup( 4486): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  904): killProcessQuiet, pid=4258
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
I/ActivityManager(  904): Killing 4258:com.google.android.apps.docs/u0a100 (adj 15): empty #17
I/ActivityManager(  904): Recipient 4258
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils-trace( 4499): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4499): ====startRecUseTime====
D/htc.customization.log.level( 4499):  is 
W/CustomizationLogLevel( 4499): Level value is invalid, use default level 2
D/CustomizationManager( 4499):  Read ACC file spent 0.064 (s)
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4499): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4499): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4499): Parsing tag category name = system
I/CustomizationCIDLoader( 4499): Parsing tag category name = application
I/CustomizationCIDLoader( 4499): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4499): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4499): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4499): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4499): Parsing tag category name = Settings
D/CustomizationManager( 4499):  Read CID file spent 0.106 (s)
D/CustomizationManager( 4499):  All configurations done spent 0.107 (s)
W/HtcNativeFlag( 4499): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4499): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4499): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4499): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  904): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  904): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4499
D/PMS     (  904): acquireHCC(434cf938): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 904 1000 null
D/PMS     (  904): acquireHCC(4350aec0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 904 1000 null
W/asset   (  904): Copying FileAsset 0x67852bd8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  904): @test_code: getHtcIntentFlag: 0 obj: 1134914456
D/PMS     (  904): acquireWL(432175c8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c54e40
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
I/ActivityManager(  904): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4510 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1271): [trimMemory] 20
W/asset   ( 4510): Copying FileAsset 0x5c769428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4510): Binding Chromium to main looper Looper (main, tid 1) {41ae9a10}
I/LibraryLoader( 4510): Expected native library version number "",actual native library version number ""
I/chromium( 4510): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4510): Initializing chromium process, renderers=0
W/System.err(  904): java.lang.Throwable: stack dump
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41e265d8:true
D/PMS     (  904): acquireWL(435cf2a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  904): acquireWL(4370ff68): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  904): releaseWL(435cf2a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4510): 1102061184: getState(). Returning 12
I/Adreno-EGL( 4510): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4510): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4510): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4510): Local Branch: 
I/Adreno-EGL( 4510): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4510): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4510):                  aa63bbd948f41d15fc72f585e
W/chromium( 4510): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4510): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4510): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4510): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4510): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4510): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4510): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4510): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4510): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4510): CordovaWebView is running on device made by: HTC
,W/AwContents( 4510): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  904): Disable input method client, pid=1271
,W/ResourceType( 4510): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4510): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b33530, mServedView=org.apache.cordova.engine.SystemWebView{41af9198 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  904): Enable input method client, pid=4510
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4510): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  904): Displayed com.test.thalitest/.MainActivity: +289ms
,D/PMS     (  904): releaseWL(432175c8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4510): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4510): JniHelper::setJavaVM(0x415c0048), pthread_self() = 1663446416
,D/PMS     (  904): acquireWL(437d1800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,D/WifiDataStallTracker(  904): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  904): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  904): updateDataStallInfo: mDataStallTxRxSum={txSum=104 rxSum=94} preTxRxSum={txSum=33 rxSum=31}
D/WifiDataStallTracker(  904): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  904): onDataStallAlarm: tag=20542 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=20543 delay=15s
,I/chromium( 4510): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
V/AlarmManager(  904): sending alarm PendingIntent{43eb7060: PendingIntentRecord{4246e178 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=102249, Int=0
D/PMS     (  904): releaseWL(437d1800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 12.000MB for 42652-byte allocation
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 26
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 130
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): [ScoreAP] + current TXpacket:134, mTXpacketCount:58, avgLinkspeed:26,mAvgTxRate54
,D/WifiStateMachine(  904): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 12.078MB for 95956-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 12.159MB for 143930-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 12.277MB for 215890-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 12.453MB for 323830-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 12.719MB for 485740-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 13.728MB for 1092904-byte allocation
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 14.632MB for 1639352-byte allocation
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 15.887MB for 2459024-byte allocation
,W/CpuWake (  904): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  904): <<release mCpuPerf_Freq wakelock
D/PMS     (  904): releaseHCC(434cf938): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  904): releaseHCC(4350aec0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4510): Grow heap (frag case) to 18.073MB for 3688532-byte allocation
,W/jxcore-log( 4510): Initializing JXcore engine
,W/jxcore-log( 4510): JXcore engine is ready
,W/jxcore-log( 4510): Starting JXcore engine
,W/jxcore-log( 4510): Platform android
W/jxcore-log( 4510): 
,W/jxcore-log( 4510): Process ARCH arm
W/jxcore-log( 4510): 
,D/PMS     (  904): acquireWL(437b7aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10074}
,V/AlarmManager(  904): sending alarm PendingIntent{426fc6c0: PendingIntentRecord{4443ad28 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453204983883, Int=0
,D/PMS     (  904): releaseWL(437b7aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/PMS     (  904): releaseWL(4370ff68): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4510): JXcore Cordova bridge is ready!
I/jxcore-log( 4510): 
,W/jxcore-log( 4510): JXcore engine is started
,D/Finsky  ( 4123): [437] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4123): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 4510): Toggling radios to true
I/jxcore-log( 4510): 
,D/BluetoothAdapter( 4510): enable(): BT is already enabled..!
,D/WifiManager( 4510): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
,W/HtcDLNAServiceManager(  904): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  904): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  904): Settings:Agentvalue: 2
W/Settings:Agent(  904): >> traceCallingStack()
,W/Settings:Agent(  904): Process.myPid(): 904
W/Settings:Agent(  904): Process.myTid(): 1308
W/Settings:Agent(  904): Process.myUid(): 1000
W/Settings:Agent(  904): 
W/Settings:Agent(  904): 
W/System.err(  904): java.lang.Throwable: stack dump
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
,W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  904): 
W/Settings:Agent(  904): << traceCallingStack(): 1(ms)
,D/WifiManager( 4510): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  904): doBoolean: DISCONNECT
D/WifiService(  904): New client listening to asynchronous messages
D/WifiService(  904): setWifiEnabled: true pid=4510, uid=10389
E/WifiService(  904): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  904): isSprintWifiRestricted(): false
I/WifiService(  904): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  904): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/WifiManager( 4510): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): TDLS: Tear down peers
I/wpa_supplicant( 1160): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4510): Radios toggled
I/jxcore-log( 4510): 
I/jxcore-log( 4510): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4510): 
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1160): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1160): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1160): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  904): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  904): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  904): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412,
D/HTCRequest(  904): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  904): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1160): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1160): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1160): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1160): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1160): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb74ddbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1160):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1160): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1160): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1160): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1160): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1160): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1160): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1160): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1160): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1160): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1160): RTM_NEWLINK: operstate=0 ifi_flags=,0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1160): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1160): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1160): Wireless event: cmd=0x8b15 len=20
D/Tethering(  904): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1160): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  904):    returned true
D/WifiPerfLock(  904): release()
D/WifiStateMachine(  904): PerfLock released for exiting ConnectedState
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  904): [isWifi] getHotspotEnabled: false
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): Power_Mode_Type mode = 0
I/wpa_supplicant( 1160): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 61
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
D/Tethering(  904): interfaceStatusChanged wlan0, false
,D/Tethering(  904): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  904):    returned true
D/ConnectivityService(  904): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  904): acquireWL(432de8d8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 904 1000 null
D/DhcpStateMachine(  904): [RunningState] Stop DHCP
D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  904): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  904): doBoolean: RECONNECT
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): Fast associate: Old scan results
I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): State: DISCONNECTED -> SCANNING
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiNative-wlan0(  904):    returned true
D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=20543 mDataStallAlarmIntent=PendingIntent{43313410: PendingIntentRecord{4246e178 android broadcastIntent}}
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  904): Enter handleNetworkDisconnect
,D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
,D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
D/libc    (  904): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): Power_Mode_Type mode = 0
I/wpa_supplicant( 1160): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  904):    returned true
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  904): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  904): Provision feature enable=false
D/ConnectivityService(  904): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  904): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/UsbnetStateTracker(  904): isAvailable+-
D/UsbnetStateTracker(  904): reconnect
,D/UsbnetStateTracker(  904): isAvailable+-
,D/WISPrService( 4107): >>>>>WISPrService start isConnected = false<<<<<
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/MDST    (  904): default: reconnect()
D/MDST    (  904): default: setTeardownRequested(false)
D/MDST    (  904): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  904): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  904): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  904): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/WISPrService( 4107): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  904): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiService(  904): New client listening to asynchronous messages
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  904): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  904): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  904): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,V/NativeCrypto( 1357): Read error: ssl=0x662ddc30: I/O error during system call, Connection timed out
,V/NativeCrypto( 1357): SSL shutdown failed: ssl=0x662ddc30: I/O error during system call, Broken pipe
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  904): handleConnectivityChange: resetting
D/ConnectivityService(  904): resetConnections(wlan0, 3)
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  904): acquireWL(437b24a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/WISPrService( 4107): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:0
D/libc    (  363): [NET] entry_id:3   entry:0xb8ee6108  removed ,
D/libc    (  363): [NET] entry_id:4   entry:0xb8ee62f0  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8ee6428  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb8ee61d0  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb8ee64f0  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb8ee5fd8  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
,D/WISPrService( 4107): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
D/ConnectivityService(  904): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  904): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  904): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  904): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  904): acquireWL(437840a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
D/ConnectivityService(  904): reportInetCondition for net -1, percentage: 0 by  (1357/10029)
,D/WirelessDisplayService(  904): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  904): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/WifiStateMachine(  904): startScan Pid: 904 Uid 1000
,D/WifiNative-wlan0(  904): doBoolean: SCAN
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  904):    returned false
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
D/PMS     (  904): releaseWL(437b24a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
D/BatSI   (  904): WIFI scan started for: 650a0301 uid:1000
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
,D/ConnectivityService(  904): mActiveDefaultNetwork: -1
,D/ConnectivityService(  904): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:1
,D/PMS     (  904): releaseWL(437840a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  904): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(43d06098): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  904): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/Tethering(  904): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  904): bSetPropertyMultiRAB:false
,D/Tethering(  904): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,D/CaptivePortalTracker(  904): NoActiveNetworkState
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): DISCONNECTED
,I/NetworkMonitor( 4328): type=WIFI subType= reason=null isConnected=false
,I/Tethering(  904): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,I/Tethering(  904): ipv4Default null
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/Tethering(  904): No IPv4 upstream interface, giving up.
,D/Tethering(  904): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.backuptransport (1537/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10076)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2113/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.google.android.music (4328/10154)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2113/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2113/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
D/ConnectivityService(  904): getActiveNetworkInfo called by  (2681/10021)
,D/GpsLocationProvider(  904): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  904): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  904): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  904): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  904): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4564 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
D/PMS     (  904): releaseWL(43d06098): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4564): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4564): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4564): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4564): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4564): Preparing secondary program dexes.
V/DexLibLoader( 4564): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4564): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4564): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4564): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
V/DexLibLoader( 4564): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
W/DexLibLoader( 4564): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4564): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4564): Dex already copied
D/OdexVerifier( 4564): Odex verification is skipped.
V/DexLibLoader( 4564): Creating class loader
V/DexLibLoader( 4564): Finished creating class loader
V/DexLibLoader( 4564): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4564): Dex already copied
D/OdexVerifier( 4564): Odex verification is skipped.
V/DexLibLoader( 4564): Creating class loader
V/DexLibLoader( 4564): Finished creating class loader
V/DexLibLoader( 4564): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4564): Dex already copied
D/OdexVerifier( 4564): Odex verification is skipped.
V/DexLibLoader( 4564): Creating class loader
,V/DexLibLoader( 4564): Finished creating class loader
V/DexLibLoader( 4564): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4564): Dex already copied
D/OdexVerifier( 4564): Odex verification is skipped.
,V/DexLibLoader( 4564): Creating class loader
V/DexLibLoader( 4564): Finished creating class loader
,V/DexLibLoader( 4564): Verifying classes from secondary dexes.
,D/DexLibLoader( 4564): DexLibLoader.ensureDexLoaded took 17 ms
,W/dalvikvm( 4564): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4564): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4564): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4564): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4564): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4564): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4564): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1160): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=10 entropy=0
D/wpa_supplicant( 1160): Add randomness: count=11 entropy=1
D/wpa_supplicant( 1160): Add randomness: count=12 entropy=2
D/wpa_supplicant( 1160): Add randomness: count=13 entropy=3
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 3
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 1
I/wpa_supplicant( 1160): wpa_s->is_screen_on 1
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): selected network = 2
D/wpa_supplicant( 1160): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb74df4e8  current_ssid=0x0
D/wpa_supplicant( 1160): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1160): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1160): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1160): check if in concurrent case
I/wpa_supplicant( 1160): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1160): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1160): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1160): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1160): RSN: PMKSA cache search - network_ctx=0xb74df4e8 try_opportunistic=0
D/wpa_supplicant( 1160): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1160): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1160): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1160): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1160): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1160): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1160): nl80211: Unsubscribe mgmt frames handle 0xb74de718 (mode change)
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1160): nl80211: Subscribe to mgmt frames with non-AP handle 0xb74de718
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb74de718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb74de718
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb74de718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb74de718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb74de718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb74de718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb74de718
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb74de718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb74de718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb74de718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1160):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1160):   * freq=2412
D/wpa_supplicant( 1160):   * Auth Type 0
D/wpa_supplicant( 1160):   * WPA Versions 0x2
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1160): nl80211: Connect request send successfully
D/wpa_supplicant( 1160): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1160): reply (489) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-46
I/wpa_supplicant( 1160): tsf=0000000107211179
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2427
I/wpa_supplicant( 1160): level=-79
I/wpa_supplicant( 1160): tsf=0000000107211202
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-57
I/wpa_supplicant( 1160): tsf=0000000107211196
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=3
I/wpa_supplicant( 1160): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-57
I/wpa_supplicant( 1160): tsf=0000000107211191
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1160): ssid=01ABC
I/wpa_supplicant( 1160): ####
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 107211179, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  904): getDiscoveryDongleList
,D/WifiStateMachine(  904): == begin of scan result ==
,D/WifiStateMachine(  904): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
,D/WirelessDisplayService(  904): getDiscoveryDongleList
D/WifiStateMachine(  904): == begin of scan result ==
,D/WifiStateMachine(  904): == (4) end of scan result ==
D/WifiStateMachine(  904): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 107211202, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WifiStateMachine(  904): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 107211196, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 107211191, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): add 4 to mScanResults
D/BatSI   (  904): WIFI scan stopped for: 640a0301 uid:1000
D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,W/dalvikvm( 4564): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4564): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1160): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1160): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1160): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1160): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1160): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1160): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1160): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1160): nl80211: Connect event
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1160): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1160): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1160): Add randomness: count=14 entropy=4
I/wpa_supplicant( 1160): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1160): TDLS: Remove peers on association
D/wpa_supplicant( 1160): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1160): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1160): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1160): EAPOL: enable timer tick
D/wpa_supplicant( 1160): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1160): htc_wext_set_keepalive +
I/wpa_supplicant( 1160): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1160): getPrivFuncNum +	
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1160): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1160): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1160): Get randomness: len=32 entropy=5
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  904): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  904): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  904): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  904): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  904): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  904): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantSt,ateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  904): Enter handleAssociatedWithEvent
D/WifiStateMachine(  904): Associated
D/WifiStateMachine(  904): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  904): Exit handleAssociatedWithEvent
D/WifiStateMachine(  904): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  904): updateConnectedAP...
D/WifiApDatabaseHandler(  904): updateConnectedAP...
D/WifiStateMachine(  904): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  904): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  904): This record is existed, only update it...
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/Tethering(  904): interfaceLinkStateChanged wlan0, false
,D/Tethering(  904): interfaceStatusChanged wlan0, false
,D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/Tethering(  904): interfaceLinkStateChanged wlan0, true
,D/Tethering(  904): interfaceStatusChanged wlan0, true
,D/Tethering(  904): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1160): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb74de9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1160):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1160): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1160): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f66b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1160):    broadcast key
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1160): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1160): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 1160): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1160): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
,D/WifiMonitor(  904): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1160): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1160): set send_ind_to_ndc = 0
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1160): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1160): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1160): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1160): EAPOL: SUPP_BE entering state SUCCESS
,D/wpa_supplicant( 1160): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1160): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1160): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1160): EAPOL authentication completed successfully
I/wpa_supplicant( 1160): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1160): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
,D/wpa_supplicant( 1160): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1160): nl80211: if_removed already cleared - ignore event
D/Tethering(  904): interfaceLinkStateChanged wlan0, true
D/Tethering(  904): interfaceStatusChanged wlan0, true
,D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED,
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/WifiStateMachine(  904): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  904): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WISPrService( 4107): >>>>>WISPrService start isConnected = false<<<<<
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  904): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  904): Provision feature enable=false
,D/ConnectivityService(  904): mActiveDefaultNetwork: -1
D/WISPrService( 4107): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiApDatabaseHandler(  904): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  904): This record is existed, only update it...
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
,D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/DhcpStateMachine(  904): [StoppedState] Start DHCP
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [2][0][0]
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
E/FbInjectorInitializer( 4564): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): Power_Mode_Type mode = 1
I/wpa_supplicant( 1160): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  904):    returned null
E/WifiStateMachine(  904): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  904): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  904):    returned null
D/WifiStateMachine(  904): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  904): acquireWL(43780458): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 904 1000 null
D/WifiStateMachine(  904): handlePreDhcpSetup mBluetoothConnectionActive: false
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiP2pService(  904): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@426ef6b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@426ef6b0 target=com.android.internal.util.StateMachine$SmHandler }
,W/fb4a(:<default>):StaticBindingVerifier( 4564): Verify
,D/WifiService(  904): New client listening to asynchronous messages
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4564): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4564): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4564): Grow heap (frag case) to 9.517MB for 73240-byte allocation
,D/Process (  904): killProcessQuiet, pid=4275
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 4275:com.htc.backup/1000 (adj 15): empty #17
,D/AutoSetting( 1314): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  904): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4591 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1314/10055)
,D/AutoSetting( 1314): Util - no network available!
,D/AutoSetting( 1314): service - onCreate()
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1314/10055)
,D/AutoSetting( 1314): service - AddressCache: using context: com.htc.Weather
,D/LocationManagerService(  904): request 42443410 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  904): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 1314): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1314): service - mHandler: cancel location update
,D/AutoSetting( 1314): service -           changes count: 0
,D/MobileConnectivityChangeReceiver( 4591): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4591): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4591): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4591): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  904): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4607 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,W/fb4a(:<default>):UserScope( 4564): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4564): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4591/10079)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4591/10079)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4591/10079)
,W/fb4a(:<default>):UserScope( 4564): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/ActivityManager(  904): Recipient 4275
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4564): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  904): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4623 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  904): killProcessQuiet, pid=4245
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Killing 4245:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4245
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/dalvikvm( 4564): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4564): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4564): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4564): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4564): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4564): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4564): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4564): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4564): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4623): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4623): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4564): Grow heap (frag case) to 9.970MB for 84664-byte allocation
E/dalvikvm( 4564): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4564): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4564): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4564): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4564): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4564): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4564): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4564): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4564): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,W/GAV2    ( 4623): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4623): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4623): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4564): Grow heap (frag case) to 9.984MB for 28144-byte allocation
,I/dalvikvm-heap( 4564): Grow heap (frag case) to 10.025MB for 39954-byte allocation
,I/dalvikvm-heap( 4564): Grow heap (frag case) to 10.101MB for 79892-byte allocation
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4623/10151)
,V/WebViewChromiumFactoryProvider( 4623): Binding Chromium to main looper Looper (main, tid 1) {41af0380}
,I/LibraryLoader( 4623): Expected native library version number "",actual native library version number ""
,I/chromium( 4623): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4623): Initializing chromium process, renderers=0
,D/PMS     (  904): acquireWL(43cd7e68): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 4623): BLUETOOTH permission is missing!
D/PMS     (  904): acquireWL(43cbcb98): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  904): releaseWL(43cbcb98): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4623): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4623): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4623): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4623): Local Branch: 
I/Adreno-EGL( 4623): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4623): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4623):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4623): Starting up...
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4623/10151)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4623/10151)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4087/10160)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4087/10160)
,D/Process (  904): killProcessQuiet, pid=4299
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 4299:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2113/10029)
,I/iu.Environment( 2113): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2113): num queued entries: 0
,I/iu.UploadsManager( 2113): num updated entries: 0
,I/iu.SyncManager( 2113): NEXT; no task
D/wpa_supplicant( 1160): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1160): EAPOL: disable timer tick
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2113/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2113/10029)
,I/dalvikvm-heap( 4564): Grow heap (frag case) to 10.289MB for 75760-byte allocation
I/ActivityManager(  904): Recipient 4299
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
D/ConnectivityService(  904): getAllNetworkInfo called by com.test.thalitest (4510/10389)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4240dd48 u0 ReceiverList{4240dff0 4564 com.facebook.katana/10027/u0 remote:420cd828}}
W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4240dd48 u0 ReceiverList{4240dff0 4564 com.facebook.katana/10027/u0 remote:420cd828}}
W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{423f6b08 u0 ReceiverList{423f7ef8 4564 com.facebook.katana/10027/u0 remote:42090838}}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
,D/PMS     (  904): acquireWL(437b24a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(437b24a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  904): mEventCount = 1050
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4564): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4564): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1160): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  904):    returned true
,D/WifiStateMachine(  904): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  904): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): releaseWL(43780458): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [2][0][0]
,I/wpa_supplicant( 1160): Change stage from stage0 to stage3
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): gateway: /192.168.1.1
,D/WifiNative-wlan0(  904): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1160): wlan0: Background scan every 600 seconds
,D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  904): VerifyingLinkState enter
D/WifiStateMachine(  904): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  904): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  904): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WIFI_ICON( 1113): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,V/NetworkPolicy(  904): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  904): startDataStallAlarm: tag=20545 delay=15s
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 4107): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiWatchdogStateMachine(  904): WAN detection
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  904): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  904): Provision feature enable=false
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  904): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  904): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  904): default: teardown()
D/MDST    (  904): default: setTeardownRequested(true)
D/MDST    (  904): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED connected
D/MDST    (  904): default: setTeardownRequested(true)
D/ConnectivityService(  904): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1113): WifiActivity: 1
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/ConnectivityService(  904): Unexpected mtu value: android.net.wifi.WifiStateTracker@42471c90
D/ConnectivityService(  904): handleConnectivityChange: netType=1 doReset=false resetMask=0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  904): syncGetConfiguredNetworks
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  904): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  904): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  904): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  904): handleConnectivityChange: resetting
D/Nat464Xlat(  904): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  904): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [2][0][0]
D/WirelessDisplayService(  904): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  904):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/ConnectivityService(  904): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  904): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  904): acquireWL(42597660): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4591/10079)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
I/QuickSettingWifi( 1113): receive.wifiConnect:true wifiAPname:NG700 elapse:0
D/PMS     (  904): acquireWL(434d3e20): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2113 10029 WorkSource{10029 com.google.android.gms}
I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2113): Checkin interval check for package: unspecified last checkin: 1453204948997 min interval config: 0 actual interval: 39506
D/PMS     (  904): acquireWL(425a9168): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2113 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(434d3e20): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2113): Checking schedule, now: 1453204988508 next: 1453204978964
I/CheckinService( 2113): active receiver: enabled
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2113, uid=10029, userID:0
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
I/CheckinService( 2113): Preparing to send checkin request
,I/EventLogService( 2113): Accumulating logs since 1453204943750
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2113/10029)
,D/ConnectivityService(  904): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/PMS     (  904): releaseWL(42597660): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/CheckinRequestBuilder( 2113): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  904): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2113): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (2113/10029)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2113/10029)
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{43d09f28 u0 com.htc.htclocationservice/.AutoSettingService}
V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  904): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4696 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4696): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4696): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4696): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4696): install
,I/MultiDex( 4696): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4696): loading existing secondary dex files
,I/MultiDex( 4696): load found 3 secondary dex files
,I/MultiDex( 4696): install done
,W/dalvikvm( 4696): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4696): VFY: unable to resolve instance field 36
,W/dalvikvm( 4696): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4696): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4696): Installed default security provider GmsCore_OpenSSL
,D/LocationInitializer( 2113): Restart initialization of location
,W/dalvikvm( 4696): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4696): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/WearableService( 1222): callingUid 10029, callindPid: 1222
,D/AuthorizationBluetoothService( 1357): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1357): Proximity feature is not enabled.
W/dalvikvm( 4696): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,E/MDM     ( 1222): [115] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
E/dalvikvm( 4696): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
,W/dalvikvm( 4696): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4696): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4696): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
D/PMS     (  904): acquireWL(446148b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(446148b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
,I/WVCdm   (  370): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  370): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4696): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  370): PrepareKeyRequest: nonce=3069339549
,I/WVCdm   (  370): CdmEngine::CloseSession
,I/jxcore-log( 4510): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4510): 
,I/Adreno-EGL( 4696): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4696): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4696): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4696): Local Branch: 
I/Adreno-EGL( 4696): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4696): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4696):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4696): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WIFI_ICON( 1113): WifiActivity: 2
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
D/PMS     (  904): releaseWL(432de8d8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  904): NetTransition Wakelock for ConnectedState released by timeout
,D/WifiStateMachine(  904): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  904): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  904): bSetPropertyMultiRAB:false
,D/Tethering(  904): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  904): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  904): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  904): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  904): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  904): Found interface wlan0
,D/Tethering(  904): TetherMasterSM: InitialState processMessage what=3
I/AlarmManager(  904): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
,D/GpsLocationProvider(  904): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  904): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/NetworkMonitor( 4328): type=WIFI subType= reason=null isConnected=true
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): CONNECTED
,D/CaptivePortalTracker(  904): NoActiveNetworkState
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
D/PMS     (  904): acquireWL(432c4e88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.backuptransport (1537/10029)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.google.android.music (4328/10154)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2113/10029)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10076)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4591/10079)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.musicenhancer (3883/10053)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/GpsLocationProvider(  904): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  904): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
D/PMS     (  904): releaseWL(432c4e88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.backuptransport (1537/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2113/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2113/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
D/PMS     (  904): acquireWL(439e48c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (2681/10021)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/PMS     (  904): releaseWL(439e48c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/AutoSetting( 1314): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4591): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4591): onReceive CONNECTIVITY_CHANGE networkType=1
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
,D/AutoSetting( 1314): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1314): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1314): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1314): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1314): service - handleMessage() setting current location null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1314/10055)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4623/10151)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1314/10055)
D/AutoSetting( 1314): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1314): service - onStartCommand() check timezone in 30000
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4087/10160)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4087/10160)
,D/PMS     (  904): acquireWL(43a74140): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2113 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2113): Checkin interval check for package: unspecified last checkin: 1453204948997 min interval config: 0 actual interval: 40599
D/PMS     (  904): releaseWL(43a74140): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2113, uid=10029, userID:0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 2113): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,I/iu.UploadsManager( 2113): num queued entries: 0
,I/iu.UploadsManager( 2113): num updated entries: 0
,I/iu.SyncManager( 2113): NEXT; no task
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2113/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2113/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2113/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
D/ConnectivityService(  904): getAllNetworkInfo called by com.test.thalitest (4510/10389)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
D/libc    ( 1357): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1357): [NET] getaddrinfo-,err=8
D/libc    ( 1357): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1357): [NET] getaddrinfo-, 1
,D/libc    ( 1357): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =e69c +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  904): acquireWL(43a6b028): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 66
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1357): [NET] getaddrinfo_proxy-, success
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/libc    ( 1357): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1357): [NET] getaddrinfo-,err=8
,V/LightsService(  904): setLight #0: color=#3f
D/libc    ( 1357): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1357): [NET] getaddrinfo-,err=8
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
,D/WVCdm   (  370): PrepareKeyRequest: nonce=4038312141
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=12 [8][1][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiStateMachine(  904): BroadcastRSSIForIMS, newrssi =-57 , oldRssi= -200
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
V/LightsService(  904): setLight #0: color=#39
D/WIFI_ICON( 1113): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,I/WVCdm   (  370): CdmEngine::CloseSession
V/LightsService(  904): setLight #0: color=#32
,V/LightsService(  904): setLight #0: color=#2b
,I/Adreno-EGL( 4696): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4696): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4696): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4696): Local Branch: 
I/Adreno-EGL( 4696): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4696): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4696):                  aa63bbd948f41d15fc72f585e
,V/LightsService(  904): setLight #0: color=#25
,I/Adreno-EGL( 4696): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4696): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4696): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4696): Local Branch: 
I/Adreno-EGL( 4696): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4696): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4696):                  aa63bbd948f41d15fc72f585e
,V/LightsService(  904): setLight #0: color=#1e
,V/LightsService(  904): setLight #0: color=#17
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (4696/10029)
,V/LightsService(  904): setLight #0: color=#14
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,W/fb4a(:<default>):UserScope( 4564): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4564): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): acquireWL(444e06f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
,D/PMS     (  904): releaseWL(43a6b028): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
,D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1357/10029)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  904): handleInetConditionChange: starting a change hold
,D/PMS     (  904): releaseWL(444e06f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(43327450): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
I/jxcore-log( 4510): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4510): 
,I/CheckinRequestBuilder( 2113): Classify the device as Phone.
,I/jxcore-log( 4510): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4510): 
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1357/10029)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1357/10029)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
D/PMS     (  904): releaseWL(43327450): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 2113): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2113): [NET] getaddrinfo-,err=8
D/libc    ( 2113): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    ( 2113): [NET] getaddrinfo-, 1
,D/libc    ( 2113): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =fa10 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=84
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2113): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2113): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2113): [NET] getaddrinfo-,err=8
,I/jxcore-log( 4510): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4510): 
,D/libc    ( 2113): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2113): [NET] getaddrinfo-,err=8
D/libc    ( 2113): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2113): [NET] getaddrinfo-,err=8
,I/jxcore-log( 4510): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4510): 
,E/fb4a(:<default>):LocalFbBroadcastManager( 4564): Called registerBroadcastReceiver twice.
,I/jxcore-log( 4510): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4510): 
,I/jxcore-log( 4510): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4510): 
,I/CheckinTask( 2113): Sending checkin request (12207 bytes)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/WIFI_ICON( 1113): WifiActivity: 3
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  904): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=20 [20][4][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): releaseWL(43cd7e68): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/CheckinRequestBuilder( 2113): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  904): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2113): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (2113/10029)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2113/10029)
,I/CheckinRequestBuilder( 2113): Classify the device as Phone.
,I/CheckinTask( 2113): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2113): Checking schedule, now: 1453204990740 next: 1453727927738
,I/CheckinService( 2113): active receiver: disabled
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2113, uid=10029, userID:0
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
,I/CheckinService( 2113): Checking schedule, now: 1453204990755 next: 1453727927738
,I/CheckinService( 2113): active receiver: disabled
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2113, uid=10029, userID:0
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
,D/CheckinService( 2113): Recording last checkin time for package unspecified as 1453204990758
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
D/PMS     (  904): releaseWL(425a9168): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1357): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2113/10029)
,D/libc    (  904): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =67ef +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  904): Find DNS Address www.htc.com/104.81.130.175
,I/GAV2    ( 4623): Thread[GAThread,5,main]: No campaign data found.
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [4][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
D/WIFI_ICON( 1113): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/jxcore-log( 4510): Test app app.js loaded
I/jxcore-log( 4510): 
,W/dalvikvm( 4510): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4510): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4510): BLE advertisement is supported
I/jxcore-log( 4510): 
,I/chromium( 4510): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  904): Killing 3484:com.htc.task/u0a71 (adj 15): empty #17
D/Process (  904): killProcessQuiet, pid=3484
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 3484
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=25 [4][1][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =2
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97",
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  904):    returned true,
D/WifiStateMachine(  904): [ScoreAP] + current TXpacket:53, mTXpacketCount:0, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  904): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB,
D/WIFI_ICON( 1113): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/SensorManager(  904): mEventCount = 1200
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PMS     (  904): Going to sleep due to screen timeout...
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@422b4928
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Light sensor
I/ActivityManager(  904): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  904): Couldn't get kernel wake lock stats
V/LightsService(  904): setLight #2: color=#0
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@422b4928, eanble = 0, strlen(mName) = 59
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  904): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41bd7850
W/SensorService(  904): Listener[1] = com.htc.smartdim.sensor_eye@446e0d00
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/qdlights(  904): set_light_buttons_func: on=0 brightness=0
V/LightsService(  904): setLight #0: color=#0
,W/PMS     (  904): mWirelessDisplayManager is null
,D/WirelessDisplayService(  904): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  904): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/SurfaceControl(  904): Excessive delay in blankDisplay() while turning screen off: 311ms
D/PMS     (  904): nativeSetInteractive:false
D/PMS     (  904): nativeSetInteractive:false done
D/PMS     (  904): nativeSetAutoSuspend:true
D/PMS     (  904): nativeSetAutoSuspend:true done
D/HABCtrl (  904): TPE algorithm. remove timeout.
D/PMS     (  904): OOBE c monitor 11
I/InputManager(  904): Cancel all due to getting PMS screen off broadcast
D/NfcService( 1255): ScreenObserver: OFF
,D/NfcService( 1255): applyRouting - 0
V/KeyguardServiceDelegate(  904): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@426f4fa0)
I/IntentController( 1113): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1255): applyRouting -2
W/ResourceType( 4510): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4510): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41af9198 VFEDH.C. .F...... 0,0-720,1134 #64}
,V/KeyguardServiceDelegate(  904): **** SHOWN CALLED ****
I/InputMethodManagerService(  904): screenObserver, isScreenOn=false
I/InputMethodManagerService(  904): Disable input method client, pid=4510
D/PMN     (  904): wakingUp
D/PMS     (  904): acquireWL(4463f328): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMS     (  904): releaseWL(4463f328): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/WindowManager(  904): No lock screen! windowToken=null
D/WirelessDisplayService(  904): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMN     (  904): onScreenOn
D/PMS     (  904): acquireWL(44483158): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
D/PMS     (  904): releaseWL(44483158): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/AlarmManager(  904): ACTION_SCREEN_ON
I/AlarmManager(  904): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done recovering
I/AlarmManager(  904): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  904): [AlarmQueuing] done EPS screen off alarm recovering
D/MtpService( 2681): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2681): [MTP][onReceive]-
D/NfcService( 1255): applyRouting - 0
,D/NfcService( 1255): applyRouting -2
D/PMS     (  904): acquireWL(43a99e40): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMS     (  904): releaseWL(43a99e40): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
,D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=20546 delay=15s
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4751 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/ClockThread( 1113): stop update clock
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): SET_SCREEN_ON:On
I/wpa_supplicant( 1160): htc_wext_set_keepalive +
I/wpa_supplicant( 1160): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1160): getPrivFuncNum +	
I/wpa_supplicant( 1160): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1160): BG scan when screen On
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): Match BG scan, scan!
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  904):    returned true
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/HtcPowerSaver(  904): << updateStatus
D/WIFI_ICON( 1113): WifiActivity: 3
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  904): updateScreenOn: false
,W/ContextImpl( 4751): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4751): isEpsOn(), nState = 0
D/PMS     (  904): acquireWL(4456c3e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4751 1000 null
,D/SmartSyncUtils( 4751): getMobilePolicyEnabled, result = true
,D/AutoSetting( 1314): receiver - intent: android.intent.action.USER_PRESENT
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  904): releaseWL(4456c3e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/AutoSetting( 1314): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/PMS     (  904): acquireWL(4471f688): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(4471f688): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): acquireWL(44446ff8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/TetherSettings( 4107): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4107): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4107): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4107): Cust_ConnectToPC   : spcsc>false
D/        ( 4107): Cust_ConnectToPC   : IPT>true
,D/        ( 4107): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4107): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1723): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1723): onScreenOn: 1453204997380
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1723): onScreenOn: 1453204997380
,E/SmartNS_Utility( 4107): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4107): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4107): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4107): onReceive:android.intent.action.USER_PRESENT
I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41bd7850
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/PMS     (  904): releaseWL(44446ff8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
W/ContextImpl( 4107): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41bd7850, eanble = 0, strlen(mName) = 91
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  904): Listener[0] = com.htc.smartdim.sensor_eye@446e0d00
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SmartNS_PSService( 4107): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4107): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4107):  defaultType:0
D/PMN     (  904): goingToSleep
D/PMS     (  904): acquireWL(439c7cd0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 904 1000 null
,D/PMS     (  904): releaseWL(439c7cd0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/dalvikvm-heap( 4564): Grow heap (frag case) to 10.985MB for 37106-byte allocation
,I/dalvikvm-heap( 4564): Grow heap (frag case) to 11.014MB for 55654-byte allocation
,I/dalvikvm-heap( 4564): Grow heap (frag case) to 11.025MB for 47990-byte allocation
D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=20546 mDataStallAlarmIntent=PendingIntent{42337f10: PendingIntentRecord{426f1a40 android broadcastIntent}}
D/AlarmManager(  904): ACTION_SCREEN_OFF
I/AlarmManager(  904): [AlarmQueuing] screen off now: 
I/AlarmManager(  904): [AlarmQueuing] data connection: true
I/AlarmManager(  904): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
D/PMS     (  904): acquireWL(43a58538): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 904 1000 null
,W/ContextImpl( 4751): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4751): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4751): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4751): isEpsOn(), nState = 0
D/WifiService(  904): New client listening to asynchronous messages
,I/dalvikvm-heap( 4564): Grow heap (frag case) to 11.084MB for 73000-byte allocation
,I/dalvikvm-heap( 4564): Grow heap (frag case) to 11.106MB for 64232-byte allocation
,D/libc    ( 4564): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4564): [NET] getaddrinfo-,err=8
D/libc    ( 4564): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4564): [NET] getaddrinfo-, 1
,D/libc    ( 4564): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d36d +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): SET_SCREEN_ON:Off
I/wpa_supplicant( 1160): htc_wext_set_keepalive +
I/wpa_supplicant( 1160): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1160): getPrivFuncNum +	
I/wpa_supplicant( 1160): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1160): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1160): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1160): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@446e0d00
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 1
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@446e0d00, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Proximity sensor
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 0
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@446e0d00, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@446e0d00
,V/SRS_Proc(  370): ParamSet string: screen_state=off
E/ActivityThread(  904): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@43d7a5b0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@43d7a5b0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/NetworkPolicy(  904): updateScreenOn: false
,D/ContactMessageStore( 1240): start background delete task...
D/ContactMessageStore( 1240): size: 0 , 0
,D/ContactMessageStore( 1240): Background delete complete
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] getTotalRam: 1873 Mb
D/PMS     (  904): acquireWL(44738878): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(44738878): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1723): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1723): onScreenOff
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1723): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1723): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1723): onScreenOff
D/PMS     (  904): acquireWL(4472be20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(4472be20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1314): service - mHandler: cancel location update
,D/AutoSetting( 1314): service -           changes count: 0
D/PMS     (  904): acquireWL(44706778): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4564 10027 null
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PMS     (  904): acquireWL(446a6f68): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4174 10111 null
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1271): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Launcher( 1271): Deferring update until onResume
,D/Launcher( 1271): waitUntilResume // bindAppsUpdated
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
,I/[PluginManager]RegisterService( 1314): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1314): handle notify Blinkfeed plugin client changed
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): releaseWL(446a6f68): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  904): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "sms"
,I/IcingCorporaProvider( 2848): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  904): Resuming delayed broadcast
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/PMS     (  904): releaseWL(43a58538): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED,
I/ActivityManager(  904): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  904): acquireWL(420f2200): PARTIAL_WAKE_LOCK  Icing 0x1 2113 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(420f2200): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4087): Grow heap (frag case) to 13.529MB for 1821008-byte allocation
D/PMS     (  904): acquireWL(42241da0): PARTIAL_WAKE_LOCK  Icing 0x1 2113 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): acquireWL(41f46df0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4087 10160 null
,I/dalvikvm-heap( 4087): Grow heap (frag case) to 15.237MB for 1821008-byte allocation
D/PMS     (  904): releaseWL(41f46df0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/dalvikvm-heap( 4087): Grow heap (frag case) to 16.971MB for 1821008-byte allocation
,D/PMS     (  904): releaseWL(42241da0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  904): acquireWL(43ac1440): PARTIAL_WAKE_LOCK  Icing 0x1 2113 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(43ac1440): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(42654078): PARTIAL_WAKE_LOCK  Icing 0x1 2113 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  904): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,W/PackageManager(  904): Unable to load service info ResolveInfo{425c0d00 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/PMS     (  904): releaseWL(42654078): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
D/PMS     (  904): acquireWL(4243a970): PARTIAL_WAKE_LOCK  Icing 0x1 2113 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(4243a970): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(437156e8): PARTIAL_WAKE_LOCK  Icing 0x1 2113 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2113): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2113): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  904): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PMS     (  904): releaseWL(437156e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(425cc718): PARTIAL_WAKE_LOCK  Icing 0x1 2113 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2113): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2848): UpdateCorporaTask done [took 390 ms] updated apps [took 390 ms] 
I/ActivityManager(  904): Resuming delayed broadcast
,D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  904): start
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1160): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=15 entropy=0
D/wpa_supplicant( 1160): Add randomness: count=16 entropy=1
D/wpa_supplicant( 1160): Add randomness: count=17 entropy=2
D/wpa_supplicant( 1160): Add randomness: count=18 entropy=3
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 9
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 0
I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1160): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1160): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1160): p2p0: Updating scan results from sibling
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/w,pa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1160): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=19 entropy=4
D/wpa_supplicant( 1160): Add randomness: count=20 entropy=5
D/wpa_supplicant( 1160): Add randomness: count=21 entropy=6
D/wpa_supplicant( 1160): Add randomness: count=22 entropy=7
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1160): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  904): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1160): reply (489) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-46
I/wpa_supplicant( 1160): tsf=0000000119908937
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2427
I/wpa_supplicant( 1160): level=-79
I/wpa_supplicant( 1160): tsf=0000000119908985
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-57
I/wpa_supplicant( 1160): tsf=0000000119908975
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=3
I/wpa_supplicant( 1160): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-57
I/wpa_supplicant( 1160): tsf=0000000107211191
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1160): ssid=01ABC
I/wpa_supplicant( 1160): ####
D/WirelessDisplayService(  904): getDiscoveryDongleList
D/WifiStateMachine(  904): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 119908937, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 119908985, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 119908975, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WifiStateMachine(  904): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 107211191, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): add 4 to mScanResults
V/ScoreHelper(  904): Only print Top 10 in ApScanList
V/ScoreHelper(  904):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  904):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  904):  + computeScore(NG700): 1
D/WifiStateMachine(  904): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 30
D/libc    (  363): [NET]res_nsend:resplen=93
D/libc    (  363): [NET]res_queryN: exit 3, ancount=3
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4564): [NET] getaddrinfo_proxy-, success
I/global  ( 4564): call createSocket() return a new socket.
D/libc    ( 4564): [NET] getaddrinfo+,hn 13(0x3137392e36302e),sn(),family 0,flags 4
D/libc    ( 4564): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  904): == begin of scan result ==
D/WifiStateMachine(  904): == (4) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  904): == begin of scan result ==
D/WifiStateMachine(  904): == (4) end of scan result ==
D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WirelessDisplayService(  904): getDiscoveryDongleList
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/LocationProviderProxy(  904): applying state to connected service
D/PMS     (  904): acquireWL(433822b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(433822b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  904): applying state to connected service
D/PMS     (  904): acquireWL(446d9100): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(446d9100): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(434b4888): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(434b4888): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
,D/ConnectivityService(  904): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  904): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
,D/libc    ( 4564): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4,
,D/libc    ( 4564): [NET] getaddrinfo-,err=8
,D/PMS     (  904): releaseWL(44706778): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,D/PMS     (  904): acquireWL(43595ef0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4564 10027 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41b7dc30 +
,I/Prism.WidgetManager( 1271): onLoadItems() +
,I/dalvikvm-heap( 4564): Grow heap (frag case) to 11.258MB for 103586-byte allocation
,I/Icing   ( 2113): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2113): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  904): releaseWL(425cc718): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1271): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1271): onLoadItems() -
,I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41b7dc30 -
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/PhoneApp( 1240): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1240): -- N1 =0
,D/PhoneApp( 1240): -- N2 =0
,D/PhoneApp( 1240): -- N3 =0
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,I/dalvikvm-heap( 4564): Grow heap (frag case) to 11.279MB for 72624-byte allocation
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{444bad10 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,I/dalvikvm-heap( 4564): Grow heap (frag case) to 11.286MB for 108440-byte allocation
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/AutoSetting( 1568): service - handleMessage() stop self
,D/AutoSetting( 1568): service - onDestroy() END
,D/AutoSetting( 1568): service - handleMessage() quit looper
,D/Process (  904): killProcessQuiet, pid=4379
,I/ActivityManager(  904): Killing 4379:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 4379
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  904): Client connection lost with reason: 4
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4564/10027)
,D/Process (  904): killProcessQuiet, pid=3883
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3883:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3883
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/global  ( 4564): I/O error closing connection
I/global  ( 4564): java.net.SocketException: Socket is closed
I/global  ( 4564): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4564): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4564): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4564): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4564): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4564): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4564): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4564): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4564): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4564): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4564): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4564): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4564): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4564): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4564): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4564): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4564): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4564): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4564): Removing a connection that never existed!
D/PMS     (  904): releaseWL(43595ef0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,D/PMS     (  904): acquireWL(43649448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(43649448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
,D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1160): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=23 entropy=8
D/wpa_supplicant( 1160): Add randomness: count=24 entropy=9
D/wpa_supplicant( 1160): Add randomness: count=25 entropy=10
D/wpa_supplicant( 1160): Add randomness: count=26 entropy=11
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 9,
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 0,
I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1160): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1160): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1160): clear disabled list - type=1,
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1160): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1160): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=27 entropy=12
D/wpa_supplicant( 1160): Add randomness: count=28 entropy=13
,D/wpa_supplicant( 1160): Add randomness: count=29 entropy=14
D/wpa_supplicant( 1160): Add randomness: count=30 entropy=15
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1160): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1160): reply (489) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-46
I/wpa_supplicant( 1160): tsf=0000000137243386
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2427
I/wpa_supplicant( 1160): level=-79
I/wpa_supplicant( 1160): tsf=0000000137243433
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-57
I/wpa_supplicant( 1160): tsf=0000000137243423
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=3
I/wpa_supplicant( 1160): bssid=c2:ff:d4:d3:aa:48,
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-57
I/wpa_supplicant( 1160): tsf=0000000107211191
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1160): ssid=01ABC
I/wpa_supplicant( 1160): ####
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 137243386, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  904): getDiscoveryDongleList
,D/WifiStateMachine(  904): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WifiP2pService(  904): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  904): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 137243433, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 137243423, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 107211191, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  904): add 4 to mScanResults
,V/ScoreHelper(  904): Only print Top 10 in ApScanList
V/ScoreHelper(  904):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  904):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  904):  + computeScore(NG700): 1
D/WifiStateMachine(  904): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  904): == begin of scan result ==,
D/WifiStateMachine(  904): == (4) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WirelessDisplayService(  904): getDiscoveryDongleList
,D/WifiStateMachine(  904): == begin of scan result ==
,D/WifiStateMachine(  904): == (4) end of scan result ==
,D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/AutoSetting( 1314): service - mHandler: update timezone
,D/AutoSetting( 1568): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1568): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1568): service - onCreate()
W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1568): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1568): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1568): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1568): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1568): service - mHandler: update timezone
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/DotMatrix( 1525): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1525): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1568): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1568): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1568): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1568): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1525): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1525): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1113): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41ca9508 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.htc.htclocationservice 3 7 3 11
,D/PMS     (  904): acquireWL(432f3b78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  904): sending alarm PendingIntent{42723aa0: PendingIntentRecord{43c5aeb8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=132922, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{4250fc38: PendingIntentRecord{4250fd20 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142159, Int=0
,D/PMS     (  904): acquireWL(434b1158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=14 [213][30][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): acquireWL(4334a110): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  904): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  904): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  904): acquireWL(43a58820): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/PMS     (  904): releaseWL(432f3b78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =90d4 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/PMS     (  904): releaseWL(4334a110): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(434b1158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(4343c890): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
,D/PMS     (  904): releaseWL(4343c890): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(436d6868): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  904): [NET] getaddrinfo_proxy-, success
I/global  (  904): call createSocket() return a new socket.
D/libc    (  904): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1160): Change stage from stage3 to stage1
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL,
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
,D/PMS     (  904): acquireWL(43a4d368): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  904): [handleDownloadXtraData] calling native_inject_xtra_data
,D/PMS     (  904): acquireWL(435aff88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1222): Vacuum at: now=1453205021831 tag=VacuumService
,D/PMS     (  904): releaseWL(436d6868): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(43a4d368): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(434c0170): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
,D/PMS     (  904): releaseWL(435aff88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
,D/PMS     (  904): releaseWL(434c0170): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(43d287c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=10 [29][3][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  904): [reportHTCStatus] eventMask = 3 , status = 0
D/GpsLocationProvider(  904): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  904):  [handleDownloadXtraData]inject done.
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
,D/PMS     (  904): releaseWL(43d287c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(437a81e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
,D/PMS     (  904): releaseWL(437a81e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(436e9920): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): releaseWL(436e9920): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(4370a108): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1160): Change stage from stage1 to stage3
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): acquireWL(4460cde0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(4460cde0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(43a93558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(4370a108): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42d69528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
,D/PMS     (  904): releaseWL(42d69528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1222): Scheduling Phenotype for one-off execution 7169 seconds from now (1453205023738)
,D/GetConfigurationSnapshotOperation( 1222): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1222): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1222): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,W/dalvikvm( 1222): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 1222): [NET] getaddrinfo-, 1
,D/libc    ( 1222): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =1f2 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=87
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1222): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/PMS     (  904): releaseWL(43a93558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(43427d78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
,D/PMS     (  904): releaseWL(43427d78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(4349c930): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=12 [8][1][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
,D/PMS     (  904): releaseWL(4349c930): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(43a58820): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  904): acquireWL(439e0238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  904): sending alarm PendingIntent{4441f660: PendingIntentRecord{43982bf0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=148745, Int=0
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1357/10029)
,D/AutoSetting( 1314): service - handleMessage() stop self
D/PMS     (  904): releaseWL(439e0238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1314): service - handleMessage() quit looper
,D/AutoSetting( 1314): service - onDestroy() END
,D/Process (  904): killProcessQuiet, pid=4402
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4402:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4402
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
,D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  904): acquireWL(434fe618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(434fe618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1160): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=31 entropy=16
D/wpa_supplicant( 1160): Add randomness: count=32 entropy=17
D/wpa_supplicant( 1160): Add randomness: count=33 entropy=18
D/wpa_supplicant( 1160): Add randomness: count=34 entropy=19
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 9
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 0
I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1160): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1160): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1160): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1160): nl80211: Received scan results (4 BSSes),
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
,I/wpa_supplicant( 1160): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1160): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=35 entropy=20
D/wpa_supplicant( 1160): Add randomness: count=36 entropy=21
D/wpa_supplicant( 1160): Add randomness: count=37 entropy=22
D/wpa_supplicant( 1160): Add randomness: count=38 entropy=23
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1160): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  904): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  904): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1160): reply (489) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-46
I/wpa_supplicant( 1160): tsf=0000000154423820
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2427
I/wpa_supplicant( 1160): level=-79
I/wpa_supplicant( 1160): tsf=0000000154423869,
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-57
I/wpa_supplicant( 1160): tsf=0000000154423859
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=3
I/wpa_supplicant( 1160): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-57
I/wpa_supplicant( 1160): tsf=0000000107211191
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1160): ssid=01ABC
I/wpa_supplicant( 1160): ####
,D/WirelessDisplayService(  904): getDiscoveryDongleList
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 154423820, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  904): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 154423869, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 154423859, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 107211191, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  904): add 4 to mScanResults
,D/WifiStateMachine(  904): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  904): Only print Top 10 in ApScanList
,V/ScoreHelper(  904):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  904):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  904):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  904):  + computeScore(NG700): 1
,D/WifiStateMachine(  904): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  904): == begin of scan result ==
D/WifiStateMachine(  904): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
,D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WirelessDisplayService(  904): getDiscoveryDongleList
D/WifiStateMachine(  904): == begin of scan result ==
,D/WifiStateMachine(  904): == (4) end of scan result ==,
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{436a3c78 u0 com.htc.htclocationservice/.AutoSettingService},
,D/PMS     (  904): acquireWL(43509d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42107ed8: PendingIntentRecord{41bb4ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=160612, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43509d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
,D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/AutoSetting( 1568): service - handleMessage() stop self
,D/AutoSetting( 1568): service - onDestroy() END
,D/AutoSetting( 1568): service - handleMessage() quit looper
D/Process (  904): killProcessQuiet, pid=4436
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4436:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4436
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1160): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-89
D/wpa_supplicant( 1160): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=39 entropy=24
D/wpa_supplicant( 1160): Add randomness: count=40 entropy=25
D/wpa_supplicant( 1160): Add randomness: count=41 entropy=26
D/wpa_supplicant( 1160): Add randomness: count=42 entropy=27
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 9
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 0
I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1160): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1160): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1160): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-89
D/wpa_supplicant( 1160): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=43 entropy=28
D/wpa_supplicant( 1160): Add randomness: count=44 entropy=29
D/wpa_supplicant( 1160): Add randomness: count=45 entropy=30
D/wpa_supplicant( 1160): Add randomness: count=46 entropy=31
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1160): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
,I/wpa_supplicant( 1160): reply (636) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-46
I/wpa_supplicant( 1160): tsf=0000000171703855
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2427
,I/wpa_supplicant( 1160): level=-79
I/wpa_supplicant( 1160): tsf=0000000171703892
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-57
I/wpa_supplicant( 1160): tsf=0000000171703881
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=3
I/wpa_supplicant( 1160): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-57
I/wpa_supplicant( 1160): tsf=0000000107211191
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1160): ssid=01ABC
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=4
I/wpa_supplicant( 1160): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-89
I/wpa_supplicant( 1160): tsf=0000000171703902
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P]
I/wpa_supplicant( 1160): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1160): ####
D/WifiP2pService(  904): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  904): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 171703855, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  904): getDiscoveryDongleList
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WifiStateMachine(  904): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 171703892, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 171703881, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 107211191, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 4: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P], level: -89, frequency: 2437, timestamp: 171703902, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  904): add 5 to mScanResults
,D/WifiStateMachine(  904): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  904): Only print Top 10 in ApScanList
,V/ScoreHelper(  904):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  904):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  904):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  904):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  76, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-89], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  904):  + computeScore(NG700): 1
,D/WifiStateMachine(  904): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  904): == begin of scan result ==
D/WifiStateMachine(  904): == (5) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  904): == begin of scan result ==
,D/WifiStateMachine(  904): == (5) end of scan result ==
,D/WirelessDisplayService(  904): getDiscoveryDongleList
D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
,D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/TelephonyReceiver( 1240): switchBindHtcMsgCursor: null
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1160): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-89
I/wpa_supplicant( 1160): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
I/wpa_supplicant( 1160): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1160): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=47 entropy=32
D/wpa_supplicant( 1160): Add randomness: count=48 entropy=33
D/wpa_supplicant( 1160): Add randomness: count=49 entropy=34
D/wpa_supplicant( 1160): Add randomness: count=50 entropy=35
D/wpa_supplicant( 1160): Add randomness: count=51 entropy=36
D/wpa_supplicant( 1160): Add randomness: count=52 entropy=37
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 9
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 0
I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1160): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 3: 9e:93:4e:3e,:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1160): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1160): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-89
,I/wpa_supplicant( 1160): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
I/wpa_supplicant( 1160): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1160): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=53 entropy=38
D/wpa_supplicant( 1160): Add randomness: count=54 entropy=39
,D/wpa_supplicant( 1160): Add randomness: count=55 entropy=40
D/wpa_supplicant( 1160): Add randomness: count=56 entropy=41
D/wpa_supplicant( 1160): Add randomness: count=57 entropy=42
D/wpa_supplicant( 1160): Add randomness: count=58 entropy=43
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
,W/wpa_supplicant( 1160): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1160): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1160): reply (817) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-46
I/wpa_supplicant( 1160): tsf=0000000189014741
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2427
I/wpa_supplicant( 1160): level=-79
I/wpa_supplicant( 1160): tsf=0000000189014777
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-57
I/wpa_supplicant( 1160): tsf=0000000189014766
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=4
I/wpa_supplicant( 1160): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-89
I/wpa_supplicant( 1160): tsf=0000000189014787
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P]
,I/wpa_supplicant( 1160): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=5
I/wpa_supplicant( 1160): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-91
I/wpa_supplicant( 1160): tsf=0000000189014797
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=UPC4688432
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=6
I/wpa_supplicant( 1160): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-91
I/wpa_supplicant( 1160): tsf=0000000189014808
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=UPC5999698
I/wpa_supplicant( 1160): ####
D/WifiP2pService(  904): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 189014741, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  904): getDiscoveryDongleList
D/WifiStateMachine(  904): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  904): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 189014777, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 189014766, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WifiStateMachine(  904): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P], level: -89, frequency: 2437, timestamp: 189014787, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 189014797, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 189014808, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  904): add 6 to mScanResults
V/ScoreHelper(  904): Only print Top 10 in ApScanList
V/ScoreHelper(  904):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  904):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  72, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-89], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  68, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  904):  + ScoreResult:  68, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  904):  + computeScore(NG700): 1
D/WifiStateMachine(  904): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  904): == begin of scan result ==
D/WifiStateMachine(  904): == (6) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
,D/WifiStateMachine(  904): == begin of scan result ==
D/WifiStateMachine(  904): == (6) end of scan result ==
D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WirelessDisplayService(  904): getDiscoveryDongleList
,D/PMS     (  904): acquireWL(43a84278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(43a84278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
,D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1160): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-89
I/wpa_supplicant( 1160): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
I/wpa_supplicant( 1160): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1160): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=59 entropy=44
D/wpa_supplicant( 1160): Add randomness: count=60 entropy=45
D/wpa_supplicant( 1160): Add randomness: count=61 entropy=46
D/wpa_supplicant( 1160): Add randomness: count=62 entropy=47
D/wpa_supplicant( 1160): Add randomness: count=63 entropy=48
D/wpa_supplicant( 1160): Add randomness: count=64 entropy=49
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
,D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 9
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 0
I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1160): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1160): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1160): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-89
I/wpa_supplicant( 1160): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
I/wpa_supplicant( 1160): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-91
D/wpa_supplicant( 1160): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=65 entropy=50
D/wpa_supplicant( 1160): Add randomness: count=66 entropy=51
D/wpa_supplicant( 1160): Add randomness: count=67 entropy=52
D/wpa_supplicant( 1160): Add randomness: count=68 entropy=53
D/wpa_supplicant( 1160): Add randomness: count=69 entropy=54
D/wpa_supplicant( 1160): Add randomness: count=70 entropy=55
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplica,nt( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1160): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1160): reply (812) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-46
I/wpa_supplicant( 1160): tsf=0000000206403803
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2427
I/wpa_supplicant( 1160): level=-79
I/wpa_supplicant( 1160): tsf=0000000206403841
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-57
I/wpa_supplicant( 1160): tsf=0000000206403830
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=4
I/wpa_supplicant( 1160): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-89
I/wpa_supplicant( 1160): tsf=0000000206403851
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1160): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=5
I/wpa_supplicant( 1160): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-91
I/wpa_supplicant( 1160): tsf=0000000206403861
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=UPC4688432
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=6
I/wpa_supplicant( 1160): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-91
I/wpa_supplicant( 1160): tsf=0000000206403871
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I,/wpa_supplicant( 1160): ssid=UPC5999698
I/wpa_supplicant( 1160): ####
D/WifiP2pService(  904): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 206403803, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 206403841, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  904): getDiscoveryDongleList
,D/WifiStateMachine(  904): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  904): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 206403830, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WifiStateMachine(  904): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -89, frequency: 2437, timestamp: 206403851, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 206403861, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 206403871, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): add 6 to mScanResults
,V/ScoreHelper(  904): Only print Top 10 in ApScanList
,V/ScoreHelper(  904):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  904):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  904):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  904):  + ScoreResult:  72, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-89], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  68, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  68, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-91], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  904):  + computeScore(NG700): 1
,D/WifiStateMachine(  904): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  904): == begin of scan result ==
D/WifiStateMachine(  904): == (6) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  904): == begin of scan result ==
D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WirelessDisplayService(  904): getDiscoveryDongleList
D/WifiStateMachine(  904): == (6) end of scan result ==
,D/PMS     (  904): acquireWL(436d5048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(436d5048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(4446e1d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42107ed8: PendingIntentRecord{41bb4ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=220612, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4446e1d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
,D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1160): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1160): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1160): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1160): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=71 entropy=56
D/wpa_supplicant( 1160): Add randomness: count=72 entropy=57
D/wpa_supplicant( 1160): Add randomness: count=73 entropy=58
D/wpa_supplicant( 1160): Add randomness: count=74 entropy=59
D/wpa_supplicant( 1160): Add randomness: count=75 entropy=60
D/wpa_supplicant( 1160): Add randomness: count=76 entropy=61
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
,D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 9
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 0
I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0,
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1160): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1160): clear disabled list - type=1
,I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1160): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1160): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1160): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
,I/wpa_supplicant( 1160): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1160): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=77 entropy=62
D/wpa_supplicant( 1160): Add randomness: count=78 entropy=63
D/wpa_supplicant( 1160): Add randomness: count=79 entropy=64
D/wpa_supplicant( 1160): Add randomness: count=80 entropy=65
D/wpa_supplicant( 1160): Add randomness: count=81 entropy=66
D/wpa_supplicant( 1160): Add randomness: count=82 entropy=67
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1160): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  904): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1160): reply (955) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-46
I/wpa_supplicant( 1160): tsf=0000000206403803
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2427
I/wpa_supplicant( 1160): level=-79
I/wpa_supplicant( 1160): tsf=0000000223694173
,I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-57
I/wpa_supplicant( 1160): tsf=0000000223694162
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=4
I/wpa_supplicant( 1160): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-89
I/wpa_supplicant( 1160): tsf=0000000206403851
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1160): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=5
I/wpa_supplicant( 1160): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-91
I/wpa_supplicant( 1160): tsf=0000000223694205
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=UPC4688432
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=6
I/wpa_supplicant( 1160): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-90
I/wpa_supplicant( 1160): tsf=0000000223694195
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
,I/wpa_supplicant( 1160): ssid=UPC5999698
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=7
I/wpa_supplicant( 1160): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-89
I/wpa_supplicant( 1160): tsf=0000000223694183
I/wpa_supplicant( 1160): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=UPC Wi-Free
I/wpa_supplicant( 1160): ####
D/WirelessDisplayService(  904): getDiscoveryDongleList
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 206403803, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  904): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 223694173, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 223694162, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  904): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  904): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -89, frequency: 2437, timestamp: 206403851, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 223694205, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 223694195, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2437, timestamp: 223694183, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  904): add 7 to mScanResults
,V/ScoreHelper(  904): Only print Top 10 in ApScanList
V/ScoreHelper(  904):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  904):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  70, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-89], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  70, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  66, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  66, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  904):  + computeScore(NG700): 1
D/WifiStateMachine(  904): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  904): == begin of scan result ==
D/WifiStateMachine(  904): == (7) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  904): == begin of scan result ==
,D/WifiStateMachine(  904): == (7) end of scan result ==
,D/WirelessDisplayService(  904): getDiscoveryDongleList
D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(432a82d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10027}
,V/AlarmManager(  904): sending alarm PendingIntent{4245d218: PendingIntentRecord{43329350 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=228375, Int=0
,I/ActivityManager(  904): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4820 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  904): sending alarm PendingIntent{42486d58: PendingIntentRecord{426ca6f8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453205093139, Int=10800000
,D/PMS     (  904): releaseWL(432a82d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.aurora (4820/10049)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024976
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025131
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025298
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025301
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025304
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025307
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026653
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026672
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029255
,D/Process (  904): killProcessQuiet, pid=4451
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4451:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4451
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(44706778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10027}
,V/AlarmManager(  904): sending alarm PendingIntent{42398ec0: PendingIntentRecord{43329350 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=238206, Int=0
,D/PMS     (  904): releaseWL(44706778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
,D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1160): nl80211: Event message available,
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1160): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1160): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1160): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1160): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=83 entropy=68
D/wpa_supplicant( 1160): Add randomness: count=84 entropy=69
D/wpa_supplicant( 1160): Add randomness: count=85 entropy=70
D/wpa_supplicant( 1160): Add randomness: count=86 entropy=71
,D/wpa_supplicant( 1160): Add randomness: count=87 entropy=72
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1160): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
,I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 9
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
,I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 0
I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1160): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1160): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (5 BSSes)
,D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1160): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1160): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1160): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=88 entropy=73
D/wpa_supplicant( 1160): Add randomness: count=89 entropy=74
D/wpa_supplicant( 1160): Add randomness: count=90 entropy=75
D/wpa_supplicant( 1160): Add randomness: count=91 entropy=76
,D/wpa_supplicant( 1160): Add randomness: count=92 entropy=77
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1160): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1,
I/wpa_supplicant( 1160): reply (813) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-46
I/wpa_supplicant( 1160): tsf=0000000241043900
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2427
I/wpa_supplicant( 1160): level=-79
I/wpa_supplicant( 1160): tsf=0000000241043937
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos,
I/wpa_supplicant( 1160): ====
,I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-57
I/wpa_supplicant( 1160): tsf=0000000241043926
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=5
I/wpa_supplicant( 1160): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-91
I/wpa_supplicant( 1160): tsf=0000000223694205
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=UPC4688432
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=6
I/wpa_supplicant( 1160): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-90
I/wpa_supplicant( 1160): tsf=0000000241043956
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=UPC5999698
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=7
I/wpa_supplicant( 1160): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1160): freq=2437
,I/wpa_supplicant( 1160): level=-89
I/wpa_supplicant( 1160): tsf=0000000241043947
I/wpa_supplicant( 1160): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=UPC Wi-Free
I/wpa_supplicant( 1160): ####
D/WirelessDisplayService(  904): getDiscoveryDongleList
D/WifiP2pService(  904): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 241043900, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WifiStateMachine(  904): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 241043937, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
V/ScoreHelper(  904): Only print Top 10 in ApScanList
V/ScoreHelper(  904):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  904): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 241043926, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 223694205, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 241043956, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2437, timestamp: 241043947, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): add 6 to mScanResults
V/ScoreHelper(  904):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  904):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  72, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  68, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  68, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  904):  + computeScore(NG700): 1
D/WifiStateMachine(  904): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  904): == begin of scan result ==
D/WifiStateMachine(  904): == (6) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  904): == begin of scan result ==
D/WifiStateMachine(  904): == (6) end of scan result ==
D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WirelessDisplayService(  904): getDiscoveryDongleList
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  904): acquireWL(437b8888): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(437b8888): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
,D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1160): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1160): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1160): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=93 entropy=78
D/wpa_supplicant( 1160): Add randomness: count=94 entropy=79
D/wpa_supplicant( 1160): Add randomness: count=95 entropy=80
D/wpa_supplicant( 1160): Add randomness: count=96 entropy=81
D/wpa_supplicant( 1160): Add randomness: count=97 entropy=82
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 9
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 0
,I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1160): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1160): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1160): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1160): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1160): BSS: last_scan_res_used=5/32 last_scan_full=0
,D/wpa_supplicant( 1160): Add randomness: count=98 entropy=83
D/wpa_supplicant( 1160): Add randomness: count=99 entropy=84
D/wpa_supplicant( 1160): Add randomness: count=100 entropy=85
D/wpa_supplicant( 1160): Add randomness: count=101 entropy=86
D/wpa_supplicant( 1160): Add randomness: count=102 entropy=87
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1160): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  904): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1160): reply (666) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-46
I/wpa_supplicant( 1160): tsf=0000000258273693
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2427
I/wpa_supplicant( 1160): level=-79
I/wpa_supplicant( 1160): tsf=0000000258273731
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-57
I/wpa_supplicant( 1160): tsf=0000000258273719
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=6
,I/wpa_supplicant( 1160): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-90
I/wpa_supplicant( 1160): tsf=0000000258273750
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=UPC5999698
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=7
I/wpa_supplicant( 1160): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-89
I/wpa_supplicant( 1160): tsf=0000000258273740
I/wpa_supplicant( 1160): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=UPC Wi-Free
I/wpa_supplicant( 1160): ####
D/WirelessDisplayService(  904): getDiscoveryDongleList
,D/WifiStateMachine(  904): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 258273693, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 258273731, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WifiStateMachine(  904): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 258273719, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 258273750, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2437, timestamp: 258273740, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  904): add 5 to mScanResults
V/ScoreHelper(  904): Only print Top 10 in ApScanList
,V/ScoreHelper(  904):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  904):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  74, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  7 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  70, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  7 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  904):  + computeScore(NG700): 1
D/WifiStateMachine(  904): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  904): == begin of scan result ==
D/WifiStateMachine(  904): == (5) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  904): == begin of scan result ==
,D/WifiStateMachine(  904): == (5) end of scan result ==
,D/WirelessDisplayService(  904): getDiscoveryDongleList
D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3,
,I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
,D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1160): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-88
D/wpa_supplicant( 1160): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=103 entropy=88
D/wpa_supplicant( 1160): Add randomness: count=104 entropy=89
D/wpa_supplicant( 1160): Add randomness: count=105 entropy=90
D/wpa_supplicant( 1160): Add randomness: count=106 entropy=91
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 9
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 0
I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1160): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1160): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1160): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1160): nl80211: Surve,y data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1160): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-88
D/wpa_supplicant( 1160): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=107 entropy=92
D/wpa_supplicant( 1160): Add randomness: count=108 entropy=93
D/wpa_supplicant( 1160): Add randomness: count=109 entropy=94
D/wpa_supplicant( 1160): Add randomness: count=110 entropy=95
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1160): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
I/wpa_supplicant( 1160): reply (808) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-46
I/wpa_supplicant( 1160): tsf=0000000275654074
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2427
I/wpa_supplicant( 1160): level=-79
I/wpa_supplicant( 1160): tsf=0000000275654112
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-57
I/wpa_supplicant( 1160): tsf=0000000275654100
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=6
I/wpa_supplicant( 1160): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-90
I/wpa_supplicant( 1160): tsf=0000000258273750
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=UPC5999698
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=7
I/wpa_supplicant( 1160): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-89
I/wpa_supplicant( 1160): tsf=0000000258273740
I/wpa_supplicant( 1160): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=UPC Wi-Free
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=8
I/wpa_supplicant( 1160): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-88
I/wpa_supplicant( 1160): tsf=0000000275654121
,I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1160): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1160): ####
D/WirelessDisplayService(  904): getDiscoveryDongleList
D/WifiP2pService(  904): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WifiStateMachine(  904): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 275654074, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 275654112, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 275654100, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 258273750, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2437, timestamp: 258273740, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 5: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -88, frequency: 2437, timestamp: 275654121, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  904): add 6 to mScanResults
,V/ScoreHelper(  904): Only print Top 10 in ApScanList
V/ScoreHelper(  904):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  904):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  72, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  72, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  68, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  904):  + computeScore(NG700): 1
D/WifiStateMachine(  904): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  904): == begin of scan result ==
D/WifiStateMachine(  904): == (6) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  904): == begin of scan result ==
D/WifiStateMachine(  904): == (6) end of scan result ==
,D/WirelessDisplayService(  904): getDiscoveryDongleList
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(42660458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42107ed8: PendingIntentRecord{41bb4ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=280612, Int=0
I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42660458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
,D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1160): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=111 entropy=96
D/wpa_supplicant( 1160): Add randomness: count=112 entropy=97
D/wpa_supplicant( 1160): Add randomness: count=113 entropy=98
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 9
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 0
I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1160): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1160): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1160): BSS: last_scan_res_use,d=3/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=114 entropy=99
D/wpa_supplicant( 1160): Add randomness: count=115 entropy=100
D/wpa_supplicant( 1160): Add randomness: count=116 entropy=101
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1160): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=1 len=6
I/wpa_supplicant( 1160): reply (518) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-46
I/wpa_supplicant( 1160): tsf=0000000292903294
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2427
I/wpa_supplicant( 1160): level=-79
I/wpa_supplicant( 1160): tsf=0000000292903332
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-57
I/wpa_supplicant( 1160): tsf=0000000292903321
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=8
I/wpa_supplicant( 1160): bssid=9e:93:4e:3e:ba:c5,
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-88
I/wpa_supplicant( 1160): tsf=0000000275654121
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1160): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1160): ####
D/WifiP2pService(  904): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WirelessDisplayService(  904): getDiscoveryDongleList
D/WifiStateMachine(  904): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  904): Only print Top 10 in ApScanList
V/ScoreHelper(  904):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  904):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 292903294, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 292903332, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 292903321, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -88, frequency: 2437, timestamp: 275654121, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  904): add 4 to mScanResults
V/ScoreHelper(  904):  + ScoreResult:  76, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-88], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  904):  + computeScore(NG700): 1
,D/WifiStateMachine(  904): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  904): == begin of scan result ==
D/WifiStateMachine(  904): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WirelessDisplayService(  904): getDiscoveryDongleList
D/WifiStateMachine(  904): == begin of scan result ==
,D/WifiStateMachine(  904): == (4) end of scan result ==
D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1160): nl80211: Event message available
,D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1160): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1160): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1160): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=117 entropy=102
D/wpa_supplicant( 1160): Add randomness: count=118 entropy=103
D/wpa_supplicant( 1160): Add randomness: count=119 entropy=104
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1160): Start print parameters
I/wpa_supplicant( 1160): wpa_s->wpa_state is 9
I/wpa_supplicant( 1160): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1160): isConcurrentMode() is 0
I/wpa_supplicant( 1160): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1160): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1160): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1160): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1160): wpa_s->reassociate is 0
I/wpa_supplicant( 1160): wpa_s->is_screen_on 0
I/wpa_supplicant( 1160): wpa_s->ifname wlan0
I/wpa_supplicant( 1160): End print parameters
I/wpa_supplicant( 1160): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1160): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1160): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1160): BSS: last_scan_res_,used=3/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=120 entropy=105
D/wpa_supplicant( 1160): Add randomness: count=121 entropy=106
D/wpa_supplicant( 1160): Add randomness: count=122 entropy=107
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): clear disabled list - type=1
I/wpa_supplicant( 1160): No suitable network found
W/wpa_supplicant( 1160): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1160): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1160): reply (376) for get BSS: id=0
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-46
I/wpa_supplicant( 1160): tsf=0000000309982396
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2427
I/wpa_supplicant( 1160): level=-79
I/wpa_supplicant( 1160): tsf=0000000309982435
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-57
I/wpa_supplicant( 1160): tsf=0000000309982422
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ####
,D/WirelessDisplayService(  904): getDiscoveryDongleList
D/WifiP2pService(  904): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 309982396, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  904): P2pEnabledState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): DefaultState{ when=-8ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  904): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 309982435, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  904): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  904): Only print Top 10 in ApScanList
V/ScoreHelper(  904):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  904):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  904):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  904):  + computeScore(NG700): 1
,D/WifiStateMachine(  904): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  904): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 309982422, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): add 3 to mScanResults
D/WifiStateMachine(  904): == begin of scan result ==
,D/WifiStateMachine(  904): == (3) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  904): == begin of scan result ==
D/WifiStateMachine(  904): == (3) end of scan result ==
,D/WirelessDisplayService(  904): getDiscoveryDongleList
D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(424d02d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(424d02d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4510): --= Surplus to requirements =--
I/jxcore-log( 4510): 
I/jxcore-log( 4510): ****TEST TOOK:  ms ****
I/jxcore-log( 4510): 
,I/jxcore-log( 4510): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4510): 
,E/cutils-trace( 4841): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4841): ====startRecUseTime====
D/htc.customization.log.level( 4841):  is 
,W/CustomizationLogLevel( 4841): Level value is invalid, use default level 2
,D/CustomizationManager( 4841):  Read ACC file spent 0.119 (s)
D/CIDMapFileReader( 4841): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4841): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4841): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4841): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4841): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4841): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4841): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4841): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4841): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4841): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4841): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4841): Parsing tag category name = system
,I/CustomizationCIDLoader( 4841): Parsing tag category name = application
I/CustomizationCIDLoader( 4841): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4841): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4841): Parsing tag category name = AudioService,
I/CustomizationCIDLoader( 4841): Parsing tag category name = ACC,
I/CustomizationCIDLoader( 4841): Parsing tag category name = Settings
D/CustomizationManager( 4841):  Read CID file spent 0.171 (s)
,D/CustomizationManager( 4841):  All configurations done spent 0.171 (s)
W/HtcNativeFlag( 4841): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4841): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4841): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4841): Fail to get flag for type 'language', use default value: -1,
,D/PackageManager(  904): deletePackageAsUser: pkg=com.test.thalitest, pid=4841, uid=2000 user=0
,I/ActivityManager(  904): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  904): killProcessQuiet, pid=4510
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,I/ActivityManager(  904): Killing 4510:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
,W/ActivityManager(  904): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  904):   Force finishing activity ActivityRecord{434a2d00 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  904): Copying FileAsset 0x67e2ff78 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  904): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  904): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1207): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  904): Got RemoteException sending setActive(false) notification to pid 4510 uid 10389
,W/PackageSettings(  904): Skipping PackageSetting{421c2f80 com.example.hello/10397} due to missing metadata
,I/ActivityManager(  904): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1525): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1525): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1525): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
D/PMS     (  904): acquireWL(4334bd10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/VoicemailCleanupService( 1296): Cleaning up data for package: com.test.thalitest
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  904): releaseWL(4334bd10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  904): WIN DEATH: Window{444d1778 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  904): Client connection lost with reason: 4
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/Launcher( 1271): Deferring update until onResume
,D/Launcher( 1271): waitUntilResume // bindAppsRemoved
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  904):   Scheme: "smsto"
I/[PluginManager]RegisterService( 1314): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 1314): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
,W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/IcingCorporaProvider( 2848): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/ActivityManager(  904): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4857 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  904): acquireWL(436ebdb0): PARTIAL_WAKE_LOCK  Icing 0x1 2113 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(436ebdb0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(435cb4e0): PARTIAL_WAKE_LOCK  Icing 0x1 2113 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2848): UpdateCorporaTask done [took 424 ms] updated apps [took 424 ms] 
,E/SQLiteDatabase( 4857): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4857): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4857): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4857): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4857): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4857): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4857): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4857): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4857): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4857): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4857): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4857): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4857): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4857): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4857): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4857): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4857): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4857): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4857): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4857): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4857): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4857): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4857): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4857): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4857): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4857): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4857): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4857): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4857): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4857): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4857): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4857): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4857): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4857): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4857): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4857): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4857): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4857): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4857): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4857): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4857): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4857): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4857): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4857): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4857): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4857): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4857): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4857): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4857): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4857): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4857): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4857): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4857): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4857): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4857): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4857): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4857): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4857): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4857): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4857): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4857): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4857): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4857): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4857): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4857): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4857): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4857): threadid=11: thread exiting with uncaught exception (group=0x416b8e30)
,E/AndroidRuntime( 4857): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4857): Process: com.google.android.apps.docs, PID: 4857
E/AndroidRuntime( 4857): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4857): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4857): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4857): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4857): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4857): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4857): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4857): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4857): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4857): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4857): 	,at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4857): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4857): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4857): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4857): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  904): App crashed! Process: com.google.android.apps.docs
,E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
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
,E/SQLiteDatabase( 4857): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4857): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4857): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4857): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4857): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4857): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4857): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4857): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4857): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4857): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4857): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4857): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4857): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4857): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4857): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4857): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4857): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4857): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4857): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4857): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4857): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4857): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4857): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4857): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4857): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4857): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4857): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4857): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4857): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4857): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4857): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4857): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4857): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4857): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4857): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4857): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4857): Opened ClientFlag.db in read-only mode
,D/Process ( 4857): killProcess, pid=4857
,D/Process ( 4857): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  904): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4877 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 4857
,I/ActivityManager(  904): Process com.google.android.apps.docs (pid 4857) has died.
,W/ContextImpl( 4877): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  904): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4891 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4877): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4877): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4877): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4877): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4877): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4877): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4877): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4877): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4877): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4877): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4877): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4877): threadid=10: thread exiting with uncaught exception (group=0x416b8e30)
,E/AndroidRuntime( 4877): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4877): Process: com.android.keychain, PID: 4877
E/AndroidRuntime( 4877): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4877): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4877): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4877): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4877): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4877): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4877): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4877): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4877): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4877): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  904): App crashed! Process: com.android.keychain
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
,D/AppTag  ( 4891): getInstance(Context context)
,D/Process ( 4877): killProcess, pid=4877
,D/Process ( 4877): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,D/AppTag  ( 4891): getInstance(Context context)
,D/AppTag  ( 4891): onCreate()
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453205196887.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 4 more
,I/ActivityManager(  904): Recipient 4877
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.android.keychain (pid 4877) has died.
,W/ActivityManager(  904): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,D/PMS     (  904): acquireWL(43a81760): PARTIAL_WAKE_LOCK  AsyncService 0x1 4087 10160 null
,D/PMS     (  904): releaseWL(43a81760): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/dalvikvm( 4123): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/Process (  904): killProcessQuiet, pid=4050
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4050:com.google.android.gm/u0a107 (adj 15): empty #17
,D/PackageBroadcastService( 2113): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 2113): Clearing selected account for com.test.thalitest
,W/PackageManager(  904): Unable to load service info ResolveInfo{432a31a0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/ChimeraCfgMgr( 2113): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2113): Module APK com.google.android.play.games already loaded
I/ActivityManager(  904): Recipient 4050
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ChimeraCfgMgr( 2113): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2113): Module APK com.google.android.play.games already loaded
I/ActivityManager(  904): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,E/SQLiteLog( 2113): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2113): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e7a5008
,W/dalvikvm( 2113): threadid=38: thread exiting with uncaught exception (group=0x416b8e30)
I/LocationSettingsChecker( 2113): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2113): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2113): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5cab1a40
,E/ActivityManager(  904): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2113): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2113): Process: com.google.android.gms, PID: 2113
E/AndroidRuntime( 2113): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2113): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2113): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2113): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2113): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2113): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2113): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2113): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2113): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2113): 	,at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2113): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2113): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2113): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2113): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2113): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2113): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2113): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2113): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2113): 	at java.lang.Thread.run(Thread.java:864)
,D/Process ( 2113): killProcess, pid=2113
,D/Process ( 2113): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  904): Recipient 2113
,I/ActivityManager(  904): Process com.google.android.gms (pid 2113) has died.
,W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  904): handleWLDeath(435cb4e0): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
,W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20999ms
D/WifiService(  904): Client connection lost with reason: 4
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20998ms
,I/ActivityManager(  904): Resuming delayed broadcast
,W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20994ms
,W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20994ms
,E/SQLiteLog( 1357): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1357): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63f49c10
,W/dalvikvm( 1357): threadid=1: thread exiting with uncaught exception (group=0x416b8e30)
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41b7dc30 +
,I/Prism.WidgetManager( 1271): onLoadItems() +
,E/ActivityManager(  904): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1357): FATAL EXCEPTION: main
E/AndroidRuntime( 1357): Process: com.google.process.gapps, PID: 1357
E/AndroidRuntime( 1357): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1357): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1357): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1357): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1357): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1357): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1357): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1357): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1357): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1357): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1357): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1357): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1357): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1357): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1357): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1357): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1357): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1357): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1357): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1357): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1357): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1357): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1357): 	... 10 more
,E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
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
,D/Process ( 1357): killProcess, pid=1357
,I/ActivityManager(  904): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4921 uid=10098 gids={50098, 3003, 5012}
D/Process ( 1357): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,I/DeviceManagement( 4921): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4921 dbg=false s=true
,I/DeviceManagement( 4921): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4921): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4921): WorkflowService: Starting workflow service
I/DeviceManagement( 4921): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b1ae88] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4921): PackageUpdateWorkflow: ==================================================
I/ActivityManager(  904): Recipient 1357
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  904): Client connection lost with reason: 4
I/DeviceManagement( 4921): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4921): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4921): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  904): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4935 uid=10099 gids={50099, 3003, 5012}
,I/ActivityManager(  904): Process com.google.process.gapps (pid 1357) has died.
,W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30854ms
,I/DeviceManagement( 4921): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4921): SessionStateController: Checking invariants...
,D/Documents( 4935): Loading roots for com.android.providers.downloads.documents
,E/SQLiteDatabase( 4935): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4935): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4935): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4935): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4935): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4935): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4935): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4935): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4935): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4935): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4935): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4935): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4935): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4935): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4935): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4935): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4935): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4935): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4935): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4935): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4935): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4935): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4935): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4935): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4935): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4935): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4935): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4935): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4935): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4935): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4935): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4935): threadid=1: thread exiting with uncaught exception (group=0x416b8e30)
,D/Documents( 4935): Loading roots for com.android.externalstorage.documents
,E/AndroidRuntime( 4935): FATAL EXCEPTION: main
E/AndroidRuntime( 4935): Process: com.android.documentsui, PID: 4935
E/AndroidRuntime( 4935): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4935): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4935): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4935): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4935): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4935): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4935): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4935): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4935): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4935): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4935): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4935): 	,at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4935): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4935): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4935): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4935): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4935): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4935): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4935): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4935): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4935): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4935): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4935): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4935): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4935): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4935): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4935): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4935): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4935): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4935): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4935): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4935): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4935): 	... 10 more
,I/ActivityManager(  904): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4949 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/Process (  904): killProcessQuiet, pid=4486
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,E/ActivityManager(  904): App crashed! Process: com.android.documentsui
I/ActivityManager(  904): Killing 4486:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
,I/ActivityManager(  904): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4961 uid=10023 gids={50023, 1028, 1015, 1023}
,I/ActivityManager(  904): Recipient 4486
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  904): killProcessQuiet, pid=4328
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  904): Killing 4328:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  904): start
I/ActivityManager(  904): Recipient 4328
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4949): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/MediaRouterService(  904): Client com.google.android.music (pid 4328): Died!
D/Process ( 4935): killProcess, pid=4935
,D/Process ( 4935): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/SQLiteDatabase( 4921): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4921): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4921): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4921): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4921): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4921): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4921): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4921): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4921): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4921): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4921): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4921): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4921): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4921): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4921): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4921): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4921): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4921): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4921): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4921): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4921): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4921): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4921): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4921): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4921): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4921): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4921): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4921): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4921): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4921): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4921): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4921): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4921): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4921): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4921): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4921): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4921): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4921): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4921): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4921): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4921): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4921): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4921): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4921): 	at java.lang.Thread.run(Thread.java:864)
W/dalvikvm( 4949): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4949): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4949): install
I/DeviceManagement( 4921): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/MultiDex( 4949): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/DeviceManagement( 4921): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.

```
