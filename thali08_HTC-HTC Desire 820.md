#### Test 564496600f5d794_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  907): releaseWL(42ad2420): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  907): acquireWL(423dbef0): PARTIAL_WAKE_LOCK  Icing 0x1 1227 10028 null
D/PMS     (  907): releaseWL(423dbef0): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  907): acquireWL(41ea4428): PARTIAL_WAKE_LOCK  Icing 0x1 1227 10028 null
D/PMS     (  907): releaseWL(41ea4428): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  907): acquireWL(42606920): PARTIAL_WAKE_LOCK  Icing 0x1 1227 10028 null
,D/PMS     (  907): releaseWL(42606920): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/WIFI_ICON( 1116): WifiActivity: 1
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
--------- beginning of /dev/log/main
E/cutils-trace( 4396): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4396): ====startRecUseTime====
D/htc.customization.log.level( 4396):  is 
W/CustomizationLogLevel( 4396): Level value is invalid, use default level 2
D/CustomizationManager( 4396):  Read ACC file spent 0.066 (s)
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4396): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4396): Parsing tag category name = system
I/CustomizationCIDLoader( 4396): Parsing tag category name = application
I/CustomizationCIDLoader( 4396): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4396): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4396): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4396): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4396): Parsing tag category name = Settings
D/CustomizationManager( 4396):  Read CID file spent 0.107 (s)
D/CustomizationManager( 4396):  All configurations done spent 0.107 (s)
W/HtcNativeFlag( 4396): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4396): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4396): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4396): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4396
D/PMS     (  907): acquireHCC(41e7fe88): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(431af650): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
W/asset   (  907): Copying FileAsset 0x65bcaf90 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1110771056
D/PMS     (  907): acquireWL(420f7670): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/FeedHostManager( 1272): [onPause]
I/FeedProviderManager( 1272): onPause
I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@420cb9f0
I/SocialFeedProvider( 1272): +onPause
I/SocialFeedProvider( 1272): -onPause
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4407 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1272): [trimMemory] 20
W/asset   ( 4407): Copying FileAsset 0x5c79c420 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4407): Binding Chromium to main looper Looper (main, tid 1) {41b2bc80}
I/LibraryLoader( 4407): Expected native library version number "",actual native library version number ""
I/chromium( 4407): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4407): Initializing chromium process, renderers=0
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42484ab0:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4407): 1102327744: getState(). Returning 12
D/PMS     (  907): acquireWL(425ee748): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): acquireWL(42546718): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): releaseWL(425ee748): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4407): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4407): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4407): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4407): Local Branch: 
I/Adreno-EGL( 4407): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4407): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4407):                  aa63bbd948f41d15fc72f585e
W/chromium( 4407): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4407): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4407): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4407): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4407): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4407): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4407): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4407): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4407): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4407): CordovaWebView is running on device made by: HTC
,W/AwContents( 4407): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  907): Disable input method client, pid=1272
W/ResourceType( 4407): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4407): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b74670, mServedView=org.apache.cordova.engine.SystemWebView{41b3a2d8 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  907): Enable input method client, pid=4407
W/AwContents( 4407): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +297ms
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4448 uid=10077 gids={50077}
D/PMS     (  907): acquireWL(43dd5ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10077}
V/AlarmManager(  907): sending alarm PendingIntent{421e7440: PendingIntentRecord{42197970 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453370555505, Int=60000
D/PMS     (  907): releaseWL(43dd5ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
D/PMS     (  907): releaseWL(420f7670): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/SMSBackup( 4448): SMSBackupAgentService started
D/SMSBackup( 4448): Checking restore status
D/SMSBackup( 4448): Restore complete
D/SMSBackup( 4448): cancelCheckAlarm
D/SMSBackup( 4448): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  907): killProcessQuiet, pid=4191
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4191:com.google.android.apps.genie.geniewidget/u0a106 (adj 15): empty #17
I/ActivityManager(  907): Recipient 4191
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): acquireWL(4209c870): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1429 10028 null
D/PMS     (  907): acquireWL(44238908): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1429 10028 null
D/PMS     (  907): releaseWL(44238908): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  907): releaseWL(4209c870): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/WIFI_ICON( 1116): WifiActivity: 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/JsMessageQueue( 4407): Set native->JS mode to OnlineEventsBridgeMode
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [2][0][0]
I/wpa_supplicant( 1176): Change stage from stage3 to stage0
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/jxcore_app_log( 4407): JniHelper::setJavaVM(0x41604048), pthread_self() = 1664105768
I/chromium( 4407): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 11.992MB for 42652-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 12.076MB for 95956-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 12.153MB for 143930-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 12.268MB for 215890-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 12.438MB for 323830-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 12.711MB for 485740-byte allocation
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 13.698MB for 1092904-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 14.623MB for 1639352-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 15.880MB for 2459024-byte allocation
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
,D/PMS     (  907): releaseHCC(41e7fe88): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=72 rxSum=58} preTxRxSum={txSum=69 rxSum=56}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=19432 Sent 0 pkts since last received, < watchdogTrigger=5
D/PMS     (  907): releaseHCC(431af650): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
D/PMS     (  907): acquireWL(4229e150): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{42600b08: PendingIntentRecord{4251f0d8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105255, Int=0
,D/PMS     (  907): releaseWL(4229e150): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19433 delay=15s
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 18.061MB for 3688532-byte allocation
,W/jxcore-log( 4407): Initializing JXcore engine
,W/jxcore-log( 4407): JXcore engine is ready
,W/jxcore-log( 4407): Starting JXcore engine
,W/jxcore-log( 4407): Platform android
W/jxcore-log( 4407): 
,W/jxcore-log( 4407): Process ARCH arm
W/jxcore-log( 4407): 
,D/PMS     (  907): releaseWL(42546718): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4407): JXcore Cordova bridge is ready!
I/jxcore-log( 4407): 
,W/jxcore-log( 4407): JXcore engine is started
,I/jxcore-log( 4407): Toggling radios to true
I/jxcore-log( 4407): 
,D/BluetoothAdapter( 4407): enable(): BT is already enabled..!
D/WifiManager( 4407): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 2
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1345
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  907): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
W/Settings:Agent(  907): << traceCallingStack(): 1(ms)
D/WifiManager( 4407): disconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiNative-wlan0(  907): doBoolean: DISCONNECT
D/WifiManager( 4407): reconnect: Base Package Name=com.test.thalitest, uid=10189
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): TDLS: Tear down peers
I/wpa_supplicant( 1176): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4407): Radios toggled
I/jxcore-log( 4407): 
D/WifiService(  907): setWifiEnabled: true pid=4407, uid=10189
D/WifiService(  907): New client listening to asynchronous messages
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true,
I/jxcore-log( 4407): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4407): 
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1176): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1176): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1176): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/wpa_supplicant( 1176): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1176): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1176): send_and_recv error -67 - cmd 12
,D/wpa_supplicant( 1176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1176): send_and_recv error -67 - cmd 12
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1176): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8360bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1176):    addr=c0:ff:d4:d3:aa:48
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 1176): send_and_recv error -2 - cmd 12
D/Tethering(  907): interfaceStatusChanged wlan0, false
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
D/wpa_supplicant( 1176): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1176): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1176): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1176): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1176): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  907):    returned true
D/WifiPerfLock(  907): release()
D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1176): Power_Mode_Type mode = 0
I/wpa_supplicant( 1176): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(43614b80): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/DhcpStateMachine(  907): [RunningState] Stop DHCP
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  907): doBoolean: RECONNECT
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): Fast associate: Old scan results
I/wpa_supplicant( 1176): wpa_supplicant_scan enter
I/wpa_supplicant( 1176): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1176): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1176): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19433 mDataStallAlarmIntent=PendingIntent{425fd940: PendingIntentRecord{4251f0d8 android broadcastIntent}}
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): Enter handleNetworkDisconnect
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
,D/UsbnetStateTracker(  907): isAvailable+-
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
,D/WISPrService( 4154): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1843/10178)
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1176): Power_Mode_Type mode = 0
I/wpa_supplicant( 1176): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WISPrService( 4154): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  907):    returned true
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiService(  907): New client listening to asynchronous messages
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 31 Failed to remove route from default table (No such process)'
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/PMS     (  907): acquireWL(421143f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10028 null
,D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/libc    (  364): [NET] entry_id:6   entry:0xb7bf7818  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb7bf7338  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb7bf6fd8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb7bf7248  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb7bf76f0  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb7bf70e8  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb7bf7410  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb7bf6d90  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/WISPrService( 4154): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4154): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1843/10178)
D/PMS     (  907): acquireWL(4203c2e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  907): releaseWL(4203c2e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  907): acquireWL(42693798): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1369/10028)
,D/BatSI   (  907): WIFI scan started for: 650a0300 uid:1000
D/WifiNative-wlan0(  907): doBoolean: SCAN
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1176): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  907):    returned false
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/PMS     (  907): releaseWL(421143f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  907): releaseWL(42693798): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  907): mActiveDefaultNetwork: -1
,D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,I/SensorManager(  907): mEventCount = 1050
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  907): bSetPropertyMultiRAB:false
,D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
I/Tethering(  907): No IPv4 upstream interface, giving up.
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4425ab88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(4425ab88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1843/10178)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1888/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10075)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1429/10028)
,D/CaptivePortalTracker(  907): NoActiveNetworkState
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/NetworkMonitor( 3874): type=WIFI subType= reason=null isConnected=false
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4292/10100)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3874/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4292/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2459/10021)
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4476 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4476): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4476): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4476): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4476): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4476): Preparing secondary program dexes.
V/DexLibLoader( 4476): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4476): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
,V/DexLibLoader( 4476): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4476): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4476): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4476): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4476): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4476): Dex already copied
D/OdexVerifier( 4476): Odex verification is skipped.
,V/DexLibLoader( 4476): Creating class loader
,V/DexLibLoader( 4476): Finished creating class loader
V/DexLibLoader( 4476): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4476): Dex already copied
D/OdexVerifier( 4476): Odex verification is skipped.
,V/DexLibLoader( 4476): Creating class loader,
V/DexLibLoader( 4476): Finished creating class loader,
V/DexLibLoader( 4476): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4476): Dex already copied
D/OdexVerifier( 4476): Odex verification is skipped.
,V/DexLibLoader( 4476): Creating class loader
,V/DexLibLoader( 4476): Finished creating class loader
V/DexLibLoader( 4476): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4476): Dex already copied
D/OdexVerifier( 4476): Odex verification is skipped.
,V/DexLibLoader( 4476): Creating class loader
,V/DexLibLoader( 4476): Finished creating class loader
,V/DexLibLoader( 4476): Verifying classes from secondary dexes.
,D/DexLibLoader( 4476): DexLibLoader.ensureDexLoaded took 17 ms,
,W/dalvikvm( 4476): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4476): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4476): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4476): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4476): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4476): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4476): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1176): nl80211: Event message available
D/wpa_supplicant( 1176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1176): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1176): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1176): nl80211: Survey data missing
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1176): Sorted scan results
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1176): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
D/wpa_supplicant( 1176): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1176): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1176): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1176): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1176): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1176): wpa_supplicant_pick_network+
I/wpa_supplicant( 1176): Selecting BSS from priority group 1
I/wpa_supplicant( 1176): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1176): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
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
I/wpa_supplicant( 1176): selected network = 1
D/wpa_supplicant( 1176): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb83624e8  current_ssid=0x0
D/wpa_supplicant( 1176): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1176): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1176): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1176): check if in concurrent case
,I/wpa_supplicant( 1176): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
D/wpa_supplicant( 1176): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1176): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1176): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1176): RSN: PMKSA cache search - network_ctx=0xb83624e8 try_opportunistic=0
D/wpa_supplicant( 1176): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1176): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1176): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT),
D/wpa_supplicant( 1176): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1176): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1176): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1176): nl80211: Unsubscribe mgmt frames handle 0xb8361718 (mode change)
D/wpa_supplicant( 1176): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8361718
D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb8361718
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb8361718
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb8361718
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb8361718
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb8361718
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb8361718
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb8361718
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb8361718
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb8361718
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1176): nl80211: Register frame type=0xd0 nl_handle=0xb8361718
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1176): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1176):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1176):   * freq=2412
D/wpa_supplicant( 1176):   * Auth Type 0
D/wpa_supplicant( 1176):   * WPA Versions 0x2
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1176): nl80211: Connect request send successfully
,D/wpa_supplicant( 1176): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1176): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1176): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1176): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 18
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987",
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1176): reply (489) for get BSS: id=0
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1176): freq=5220
I/wpa_supplicant( 1176): level=-47
I/wpa_supplicant( 1176): tsf=0000000108751135
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG7005g
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=1
I/wpa_supplicant( 1176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412,
I/wpa_supplicant( 1176): level=-54
I/wpa_supplicant( 1176): tsf=0000000108751151
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1176): ssid=NG700
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=2
I/wpa_supplicant( 1176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-73
I/wpa_supplicant( 1176): tsf=0000000108751156
I/wpa_supplicant( 1176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1176): ssid=Gonzos
I/wpa_supplicant( 1176): ====
I/wpa_supplicant( 1176): id=3
I/wpa_supplicant( 1176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): freq=2412
I/wpa_supplicant( 1176): level=-54
I/wpa_supplicant( 1176): tsf=0000000108751146
I/wpa_supplicant( 1176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1176): ssid=01ABC
I/wpa_supplicant( 1176): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 108751135, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 108751151, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 108751156, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 108751146, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
D/BatSI   (  907): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/dalvikvm( 4476): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1176): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1176): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1176): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1176): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1176): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1176): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1176): nl80211: if_removed already cleared - ignore event
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
D/wpa_supplicant( 1176): Add randomness: count=10 entropy=4
I/wpa_supplicant( 1176): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1176): TDLS: Remove peers on association
D/wpa_supplicant( 1176): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1176): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1176): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1176): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1176): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1176): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1176): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1176): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1176): EAPOL: enable timer tick
D/wpa_supplicant( 1176): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1176): htc_wext_set_keepalive +
I/wpa_supplicant( 1176): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1176): getPrivFuncNum +	
I/wpa_supplicant( 1176): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1176): htc_wext_set_keepalive fnum = 0x8bf6
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1176): htc_wext_set_keepalive - ret = 0
D/Tethering(  907): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1176): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1176): Get randomness: len=32 entropy=5
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:g,etSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/WifiStateMachine(  907): Associated
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
D/WifiStateMachine(  907): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  907): updateConnectedAP...
I/wpa_supplicant( 1176): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb83619f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1176):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1176): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1176): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f46b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1176):    broadcast key
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1176): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1176): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1176): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1176): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1176): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1176): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1176): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1176): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1176): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1176): set send_ind_to_ndc = 0
I/wpa_supplicant( 1176): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1176): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1176): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1176): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1176): EAPOL: SUPP_PAE entering state AUTHENTICATING
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
D/wpa_supplicant( 1176): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): fetchFrequency(), freq = 2412
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/WISPrService( 4154): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4154): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
W/dalvikvm( 4476): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/DhcpStateMachine(  907): [StoppedState] Start DHCP
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(432e0cc0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
,D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1176): Power_Mode_Type mode = 1
I/wpa_supplicant( 1176): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null,
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425d2a60 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425d2a60 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,E/FbInjectorInitializer( 4476): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4476): Verify
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4476): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4476): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4476): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=3307
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3307:com.android.defcontainer/u0a19 (adj 15): empty #17
,D/PMS     (  907): acquireWL(432674f8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1227 10028 null
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3307
,D/PMS     (  907): acquireWL(43554ec0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1227 10028 null
,D/PMS     (  907): releaseWL(432674f8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10028)
,D/PMS     (  907): releaseWL(43554ec0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1369): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10028)
,D/AutoSetting( 1397): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4505 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1397/10053)
,D/AutoSetting( 1397): Util - no network available!
,D/AutoSetting( 1397): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1397): service - mHandler: cancel location update
,D/AutoSetting( 1397): service -           changes count: 0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1397/10053)
,W/fb4a(:<default>):UserScope( 4476): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4476): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4476): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4505): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4505): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4505): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4505): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4519 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3856
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3856:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4505/10078)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4505/10078)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4505/10078)
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4476): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4536 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=4233
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,E/dalvikvm( 4476): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4476): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
I/ActivityManager(  907): Killing 4233:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4233
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,I/dalvikvm-heap( 4476): Grow heap (frag case) to 9.960MB for 84664-byte allocation
E/dalvikvm( 4476): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4476): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4476): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4476): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4536): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4536): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4536): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4536): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4536): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/dalvikvm-heap( 4476): Grow heap (frag case) to 9.978MB for 28144-byte allocation
E/dalvikvm( 4476): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4476): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4476): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4476): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4476): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3856
W/dalvikvm( 4476): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4476): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4476): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4476): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4476): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4476): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4476): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4476): Grow heap (frag case) to 10.021MB for 39954-byte allocation
,I/dalvikvm-heap( 4476): Grow heap (frag case) to 10.097MB for 79892-byte allocation
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4536/10151)
,V/WebViewChromiumFactoryProvider( 4536): Binding Chromium to main looper Looper (main, tid 1) {41b32240}
,I/LibraryLoader( 4536): Expected native library version number "",actual native library version number ""
,I/chromium( 4536): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4536): Initializing chromium process, renderers=0
,D/PMS     (  907): acquireWL(4422b108): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  907): acquireWL(4425ca30): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,I/PMS     (  907): Going to sleep due to screen timeout...
,E/AudioManagerAndroid( 4536): BLUETOOTH permission is missing!
I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42220220
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42220220, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420f1008
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@42412060
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
D/PMS     (  907): releaseWL(4422b108): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #0: color=#0
,D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,I/Adreno-EGL( 4536): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4536): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4536): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4536): Local Branch: 
I/Adreno-EGL( 4536): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4536): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4536):                  aa63bbd948f41d15fc72f585e
W/PMS     (  907): mWirelessDisplayManager is null
,I/NSApplication( 4536): Starting up...
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4536/10151)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4536/10151)
,D/wpa_supplicant( 1176): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1176): EAPOL: disable timer tick
,I/dalvikvm-heap( 4476): Grow heap (frag case) to 10.280MB for 75760-byte allocation
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{431a37a8 u0 ReceiverList{43004a58 4476 com.facebook.katana/10026/u0 remote:42fe4bb0}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{431a37a8 u0 ReceiverList{43004a58 4476 com.facebook.katana/10026/u0 remote:42fe4bb0}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{437cd588 u0 ReceiverList{43743828 4476 com.facebook.katana/10026/u0 remote:4368ddb0}}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026),
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
,D/PMS     (  907): acquireWL(437a7da8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1429 10028 null
,D/PMS     (  907): releaseWL(437a7da8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1429): Unknown pending intent to remove.
D/PMS     (  907): acquireWL(44285750): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1429 10028 null
D/PMS     (  907): releaseWL(44285750): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4476): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4476): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 392ms
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
D/PMS     (  907): OOBE c monitor 11
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
,I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
D/NfcService( 1255): ScreenObserver: OFF
D/NfcService( 1255): applyRouting - 0
,D/NfcService( 1255): applyRouting -2
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43d0ccc0)
,I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
D/PMS     (  907): acquireWL(43853160): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMN     (  907): wakingUp
D/PMS     (  907): releaseWL(43853160): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  907): No lock screen! windowToken=null
D/PMN     (  907): onScreenOn
,I/InputMethodManagerService(  907): Disable input method client, pid=4407
,D/PMS     (  907): acquireWL(43e3c8d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,W/ResourceType( 4407): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4407): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b3a2d8 VFEDH.C. .F...... 0,0-720,1134 #64}
D/PMS     (  907): releaseWL(43e3c8d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/MtpService( 2459): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2459): [MTP][onReceive]-
,D/NfcService( 1255): applyRouting - 0
,D/NfcService( 1255): applyRouting -2
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  907): acquireWL(43e2ed00): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/ClockThread( 1116): stop update clock
D/PMS     (  907): releaseWL(43e2ed00): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4132/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4132/10160)
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/Process (  907): killProcessQuiet, pid=3985
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3985:com.google.android.gm/u0a107 (adj 15): empty #17
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1843/10178)
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1176): SET_SCREEN_ON:On
I/wpa_supplicant( 1176): htc_wext_set_keepalive +
I/wpa_supplicant( 1176): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1176): getPrivFuncNum +	
I/wpa_supplicant( 1176): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1176): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1176): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1176): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1176): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
D/ConnectivityService(  907): getAllNetworkInfo called by com.test.thalitest (4407/10189)
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1843/10178)
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  372): ParamSet string: screen_state=on
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/GCM     ( 1369): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/NetworkPolicy(  907): updateScreenOn: false
D/AutoSetting( 1397): receiver - intent: android.intent.action.USER_PRESENT
D/AutoSetting( 1397): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/TetherSettings( 4154): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4154): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4154): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4154): Cust_ConnectToPC   : spcsc>false
D/        ( 4154): Cust_ConnectToPC   : IPT>true
,D/        ( 4154): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4154): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4154): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4154): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4154): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4154): onReceive:android.intent.action.USER_PRESENT
,W/ContextImpl( 4154): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 4154): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4154): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4154):  defaultType:0
,I/ActivityManager(  907): Recipient 3985
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4588 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1809): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1809): onScreenOn: 1453370562327
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1809): onScreenOn: 1453370562327
D/PMS     (  907): acquireWL(42b33538): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1429 10028 null
D/PMS     (  907): releaseWL(42b33538): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420f1008
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420f1008, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@42412060
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
,D/PMS     (  907): acquireWL(43876a08): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,W/ContextImpl( 4588): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  907): releaseWL(43876a08): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19434 mDataStallAlarmIntent=null
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1176): SET_SCREEN_ON:Off
I/wpa_supplicant( 1176): htc_wext_set_keepalive +
I/wpa_supplicant( 1176): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1176): getPrivFuncNum +	
I/wpa_supplicant( 1176): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1176): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1176): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1176): get_ip_address source addr = 02000000
I/wpa_supplicant( 1176): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1176): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  907):    returned true
D/PMS     (  907): acquireWL(43ddb730): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43ddb730): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/PMS     (  907): acquireWL(4421f650): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4588 1000 null
D/SmartSyncUtils( 4588): isEpsOn(), nState = 0
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/NetworkPolicy(  907): updateScreenOn: false
,D/ContactMessageStore( 1244): start background delete task...
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
D/PMS     (  907): releaseWL(4421f650): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4588): getMobilePolicyEnabled, result = true
,D/Process (  907): killProcessQuiet, pid=4262
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  907): Killing 4262:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4262
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4588): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4588): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4588): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4588): getMobilePolicyEnabled, result = true
,D/WifiService(  907): New client listening to asynchronous messages
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42412060
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42412060, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42412060, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42412060
D/AutoSetting( 1397): service - mHandler: cancel location update
,D/AutoSetting( 1397): service -           changes count: 0
,E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4232d9d8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4232d9d8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] getTotalRam: 1873 Mb
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1809): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1809): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1809): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1809): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1809): onScreenOff
D/PMS     (  907): acquireWL(4366ffb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1429 10028 null
D/PMS     (  907): releaseWL(4366ffb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1176): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1176): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1176): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiP2pService(  907): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  907): releaseWL(432e0cc0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): gateway: /192.168.1.1
,D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1176): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1176): htc_wext_set_keepalive +
I/wpa_supplicant( 1176): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1176): getPrivFuncNum +	
I/wpa_supplicant( 1176): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1176): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1176): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1176): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1176): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState,
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
,D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -54, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiWatchdogStateMachine(  907): WAN detection
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
,D/WISPrService( 4154): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1843/10178)
D/MDST    (  907): default: setTeardownRequested(true)
,D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@4245d810
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
,D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  907): acquireWL(441c3a18): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4505/10078)
,D/PMS     (  907): acquireWL(43ee1698): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1227 10028 null
I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  907): acquireWL(43eb37c8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1227 10028 null
D/PMS     (  907): releaseWL(43ee1698): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10028)
I//system/bin/ip(  364): RTNETLINK answers: No such process
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
I/CheckinService( 1227): Preparing to send checkin request
I/EventLogService( 1227): Accumulating logs since 1453370506024
,I/GoogleHttpClient( 1227): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1227): Using GMS GoogleHttpClient
D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  907): releaseWL(441c3a18): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1227/10028)
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1227/10028)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1227): awaiting user notification for token
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41e8bac0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 9 2 12
,I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4643 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4643): install
,I/MultiDex( 4643): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4643): loading existing secondary dex files
,I/MultiDex( 4643): load found 1 secondary dex files
,I/MultiDex( 4643): install done
,I/ProviderInstaller( 4643): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1369): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/jxcore-log( 4407): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4407): 
,I/Adreno-EGL( 4643): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4643): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4643): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4643): Local Branch: 
I/Adreno-EGL( 4643): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4643): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4643):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4643): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4643): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4643): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4643): Local Branch: 
I/Adreno-EGL( 4643): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4643): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4643):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  907): releaseWL(43614b80): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1888/1000)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/CaptivePortalTracker(  907): NoActiveNetworkState
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(43668d28): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3895/10051)
I/acms    ( 1888): Checking Certificates
I/acms    ( 1888): Checking Developer Certificates
I/acms    ( 1888): Checking Application Certificates
I/acms    ( 1888): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1888): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1888): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1888): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1888): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1888): Updating next query delay: 75600000
I/mlserverapp( 1888): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1888): cancelACMSProgrammedChecks
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4292/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4505/10078)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1429/10028)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3874/10154)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTED
,I/NetworkMonitor( 3874): type=WIFI subType= reason=null isConnected=true
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1843/10178)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10075)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4643/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  907): Found interface wlan0
D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1429/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(41b8bf18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4292/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1176): Change stage from stage0 to stage3
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/ExternalAccountType( 1330): Unsupported attribute readOnly
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2459/10021)
D/PMS     (  907): acquireWL(4236f570): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4666 uid=10106 gids={50106, 3003, 5012}
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(41b8bf18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  907): releaseWL(43668d28): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
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
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/PMS     (  907): acquireWL(4268b1c0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1227 10028 null
D/PMS     (  907): releaseWL(4268b1c0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1369): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1369/10028)
D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1369): [NET] getaddrinfo-,err=8
D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1369): [NET] getaddrinfo-, 1
,D/libc    ( 1369): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,W/fb4a(:<default>):UserScope( 4476): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/libc    (  364): [NET] +++++ res_nsend xid =de11 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,W/fb4a(:<default>):UserScope( 4476): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  907): acquireWL(425a6720): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1369 10028 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10028)
,D/AutoSetting( 1397): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4505): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4505): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1397/10053)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [2][0][0]
,D/AutoSetting( 1397): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1397): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1397/10053)
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/AutoSetting( 1397): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1397): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4536/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
W/Settings( 4643): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 141
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4132/10160)
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1369): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4132/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1843/10178)
I/Adreno-EGL( 4643): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4643): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4643): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4643): Local Branch: 
I/Adreno-EGL( 4643): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4643): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4643):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  907): getAllNetworkInfo called by com.test.thalitest (4407/10189)
,I/jxcore-log( 4407): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4407): 
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
,I/jxcore-log( 4407): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4407): 
,I/dalvikvm-heap( 4132): Grow heap (frag case) to 13.515MB for 1821008-byte allocation
,D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1369): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  907): acquireWL(42601228): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
D/PMS     (  907): releaseWL(42601228): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/jxcore-log( 4407): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4407): 
,I/jxcore-log( 4407): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4407): 
,I/jxcore-log( 4407): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4407): 
,I/jxcore-log( 4407): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4407): 
,I/NewsWeather( 4666): LocationClient connecting
,E/fb4a(:<default>):LocalFbBroadcastManager( 4476): Called registerBroadcastReceiver twice.
,I/NewsWeather( 4666): NewsAccounts: 2, AllSystemAccounts 1.
,I/CheckinTask( 1227): Sending checkin request (9020 bytes)
D/libc    ( 1227): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1227): [NET] getaddrinfo-,err=8
E/dalvikvm( 4666): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4666): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
D/libc    ( 1227): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1227): [NET] getaddrinfo-, 1
,D/libc    ( 1227): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =ad8d +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
E/dalvikvm( 4666): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4666): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4666): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,D/GCM     ( 1369): Connected
D/PMS     (  907): acquireWL(42c87cb8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10028 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  907): releaseWL(425a6720): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1369/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  907): releaseWL(42c87cb8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  907): acquireWL(42fef2b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10028 null
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 164
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1227): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1369/10028)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1369/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1369): Message class mpf
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1369/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1369/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1369/10028)
D/PMS     (  907): releaseWL(42fef2b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  907): acquireWL(424f9570): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
D/PMS     (  907): releaseWL(424f9570): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/libc    ( 1227): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1227): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
,I/ProviderInstaller( 4666): Installed default security provider GmsCore_OpenSSL
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
I/NewsWeather( 4666): Last usage 0, idle 1453370564s, sync interval 2592000s
,I/NewsWeather( 4666): setPeriodicSync in seconds 2592000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4476/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42a90c60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42a90c60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4666): onConnected null
,D/PMS     (  907): acquireWL(4423c858): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1429 10028 null
,W/GCoreFlp( 1429): No location to return for getLastLocation()
,I/NewsWeather( 4666): LocationClient onConnected: location null
D/PMS     (  907): acquireWL(42a3edf8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1429 10028 null
D/PMS     (  907): releaseWL(4423c858): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  907): releaseWL(42a3edf8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4666): Skip sync for lookup editions
,I/NewsWeather( 4666): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4666): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41b54ee8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/NewsWeather( 4666): Unrecoverable authentication exception
E/NewsWeather( 4666): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4666): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4666): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4666): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
I/RemoteViews.Performance( 1116): com.google.android.gms 0 7 2 12
D/libc    ( 4666): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4666): [NET] getaddrinfo-,err=8
D/libc    ( 4666): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4666): [NET] getaddrinfo-, 1
D/libc    ( 4666): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3101 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=70
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4666): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4666): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4666): [NET] getaddrinfo-,err=8
,D/PMS     (  907): releaseWL(4425ca30): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1176): environment dirty rate=13 [30][4][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/NewsWeather( 4666): Failed to syncNewsAppData
,E/NewsWeather( 4666): Down sync of news app Failed, error code: SYNC_IO_ERROR
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(43842c20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
D/PMS     (  907): releaseWL(43842c20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4361f3b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 67959, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  907): releaseWL(4236f570): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/Process (  907): killProcessQuiet, pid=4292
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4292:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/PMS     (  907): releaseWL(4361f3b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1429/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(442e62c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(442e62c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PMS     (  907): acquireWL(44248630): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
,D/PMS     (  907): releaseWL(44248630): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/ExternalAccountType( 1330): Unsupported attribute readOnly
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1227/10028)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=50 [2][1][0]
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1227/10028)
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 1227): awaiting user notification for token
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41b8c4e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 9 2 12
I/ActivityManager(  907): Recipient 4292
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/CheckinTask( 1227): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1227): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10028)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10028)
,D/GCM     ( 1369): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  907): releaseWL(43eb37c8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1227): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bea460 that was originally bound here
E/ActivityThread( 1227): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bea460 that was originally bound here
E/ActivityThread( 1227): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1227): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1227): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1227): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1227): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1227): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1227): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1227): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1227): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1227): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1227): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1227): 	at bks.a(SourceFile:298)
E/ActivityThread( 1227): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1227): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1227): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1227): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1369): GCM config loaded
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/libc    (  364): [NET] +++++ res_nsend xid =a09d +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19,
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4,
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success,
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/104.81.130.175,
,D/AutoSetting( 1510): service - handleMessage() stop self
,D/AutoSetting( 1510): service - onDestroy() END
,D/AutoSetting( 1510): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4308
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4308:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4308
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV2    ( 4536): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 4666): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  907): killProcessQuiet, pid=4279
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4279:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4279
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 4407): Test app app.js loaded
I/jxcore-log( 4407): 
,W/dalvikvm( 4407): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4407): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4407): BLE advertisement is supported
I/jxcore-log( 4407): 
,I/chromium( 4407): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(4261e460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42168730: PendingIntentRecord{42394160 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=128079, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4261e460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43644ef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(43644ef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(43d33ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41db5d08: PendingIntentRecord{424d0068 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=133029, Int=0
,D/PMS     (  907): acquireWL(441bf308): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43d33ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(44236658): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(441bf308): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(44236658): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): acquireWL(437a7f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10028}
,V/AlarmManager(  907): sending alarm PendingIntent{41f8c388: PendingIntentRecord{4251f250 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140720, Int=0
V/AlarmManager(  907): sending alarm PendingIntent{42404bb8: PendingIntentRecord{4250dcc0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140957, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{42b6bda0: PendingIntentRecord{4263a440 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1453370589517, Int=1800000
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1369/10028)
,D/PMS     (  907): acquireWL(4422c438): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
,D/PMS     (  907): releaseWL(4422c438): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(42719520): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =fb17 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  907): acquireWL(42e7cdf8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1227 10028 null
D/PMS     (  907): releaseWL(437a7f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,I/EventLogService( 1227): Aggregate from 1453370563034 (log), 1453368789482 (data)
D/PMS     (  907): acquireWL(42cfb278): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1227 10028 null
D/PMS     (  907): releaseWL(42e7cdf8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/PMS     (  907): releaseWL(42cfb278): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/AutoSetting( 1397): service - mHandler: update timezone
,D/AutoSetting( 1397): service - handleMessage() stop self
,D/AutoSetting( 1510): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1510): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1510): service - onCreate()
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1510): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1510): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1397): service - handleMessage() quit looper
,D/AutoSetting( 1397): service - onDestroy() END
,D/AutoSetting( 1510): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1510): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1510): service - mHandler: update timezone
D/DotMatrix( 1589): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1510): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1510): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1510): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1510): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/PhoneStatusBar( 1116): removeNotification.gc:55
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41b6c968 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 3 7 2 11
,D/PMS     (  907): releaseWL(42719520): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Process (  907): killProcessQuiet, pid=3895
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3895:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3895
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{43deca70 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  907): acquireWL(42ceeb00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/PMS     (  907): acquireWL(42f3f848): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,V/AlarmManager(  907): sending alarm PendingIntent{41db5d08: PendingIntentRecord{424d0068 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=163048, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42ddf418): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42ceeb00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=7 [57][4][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(441b2760): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(42f3f848): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(42ddf418): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(441b2248): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,I/NewsWeather( 4666): Last usage 0, idle 1453370615s, sync interval 2592000s
,I/NewsWeather( 4666): setPeriodicSync in seconds 2592000
D/PMS     (  907): releaseWL(441b2248): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4666): Skip sync for lookup editions
,I/NewsWeather( 4666): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4666): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 4666): Unrecoverable authentication exception
E/NewsWeather( 4666): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4666): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4666): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4666): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41b96648 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 15 6 12
,D/PMS     (  907): acquireWL(432cee38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
E/NewsWeather( 4666): Failed to syncNewsAppData
,E/NewsWeather( 4666): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  907): releaseWL(432cee38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(441c5ba0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 113008, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  907): releaseWL(441b2760): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/PMS     (  907): releaseWL(441c5ba0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1429/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42ca86c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42ca86c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1330): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(434a1790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(434a1790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1510): service - handleMessage() stop self
,D/AutoSetting( 1510): service - onDestroy() END
,D/AutoSetting( 1510): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4332
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4332:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4332
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
,D/PMS     (  907): acquireWL(436827e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42168730: PendingIntentRecord{42394160 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=188080, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(436827e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(432d97c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(432d97c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43433df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41db5d08: PendingIntentRecord{424d0068 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=193113, Int=0
,D/PMS     (  907): acquireWL(42696c50): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43433df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4387a000): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42696c50): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(4387a000): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): acquireWL(43372660): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41db5d08: PendingIntentRecord{424d0068 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=228362, Int=0
,D/PMS     (  907): acquireWL(4333e338): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43372660): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(442494f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=13 [22][3][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1176): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(442ef328): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 907 1000 WorkSource{10106}
,E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1176): nl80211: survey data missing!
E/wpa_supplicant( 1176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1176): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(4333e338): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  907): releaseWL(442494f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4462a3e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(4462a3e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4666): Last usage 0, idle 1453370680s, sync interval 2592000s
I/NewsWeather( 4666): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4666): Skip sync for lookup editions
,I/NewsWeather( 4666): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4666): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1369): GoogleAccountDataService.getToken()
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1369): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1369): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,E/NewsWeather( 4666): Unrecoverable authentication exception
E/NewsWeather( 4666): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4666): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4666): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4666): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4666): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41cd1c58 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 2 8 4 12
,D/PMS     (  907): acquireWL(4347d8e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10028 null
E/NewsWeather( 4666): Failed to syncNewsAppData
,E/NewsWeather( 4666): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  907): releaseWL(4347d8e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(434417c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 163514, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  907): releaseWL(442ef328): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PMS     (  907): releaseWL(434417c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1429/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43102dc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  907): releaseWL(43102dc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/ExternalAccountType( 1330): Unsupported attribute readOnly
,D/PMS     (  907): acquireWL(42660a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10026}
,V/AlarmManager(  907): sending alarm PendingIntent{41bf30f0: PendingIntentRecord{42898328 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=230268, Int=0
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4721 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{4256f558: PendingIntentRecord{4257e4c8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453370671677, Int=10800000
,D/PMS     (  907): releaseWL(42660a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4721/10047)
,D/Process (  907): killProcessQuiet, pid=4350
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4350:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4350
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(425a3028): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-,
D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(425a3028): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/PMS     (  907): acquireWL(4259f840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10026}
,V/AlarmManager(  907): sending alarm PendingIntent{43411a20: PendingIntentRecord{4355f250 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=230270, Int=120000
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,V/AlarmManager(  907): sending alarm PendingIntent{425bfb48: PendingIntentRecord{42898328 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=230578, Int=0
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,D/PMS     (  907): releaseWL(4259f840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10028)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(423e6c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42168730: PendingIntentRecord{42394160 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=248079, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(423e6c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4212d2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(4212d2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(42325ca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41db5d08: PendingIntentRecord{424d0068 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=258435, Int=0
,D/PMS     (  907): acquireWL(4218d070): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): releaseWL(42325ca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(41f5a200): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(4218d070): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(41f5a200): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(42f5de00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(42f5de00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4407): --= Surplus to requirements =--
I/jxcore-log( 4407): 
I/jxcore-log( 4407): ****TEST TOOK:  ms ****
I/jxcore-log( 4407): 
,I/jxcore-log( 4407): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4407): 
,E/cutils-trace( 4745): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4745): ====startRecUseTime====
D/htc.customization.log.level( 4745):  is 
,W/CustomizationLogLevel( 4745): Level value is invalid, use default level 2
,D/CustomizationManager( 4745):  Read ACC file spent 0.122 (s)
D/CIDMapFileReader( 4745): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4745): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4745): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4745): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4745): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4745): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4745): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4745): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4745): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4745): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4745): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4745): Parsing tag category name = system
,I/CustomizationCIDLoader( 4745): Parsing tag category name = application
I/CustomizationCIDLoader( 4745): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4745): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4745): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 4745): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 4745): Parsing tag category name = Settings
D/CustomizationManager( 4745):  Read CID file spent 0.179 (s)
,D/CustomizationManager( 4745):  All configurations done spent 0.179 (s)
,W/HtcNativeFlag( 4745): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4745): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4745): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4745): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4745, uid=2000 user=0
,I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
,D/Process (  907): killProcessQuiet, pid=4407
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,I/ActivityManager(  907): Killing 4407:com.test.thalitest/u0a189 (adj 0): stop com.test.thalitest
,W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  907):   Force finishing activity ActivityRecord{42330058 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  907): Copying FileAsset 0x62760f68 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
,W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 4407 uid 10189
E/JavaBinder( 1208): !!! FAILED BINDER TRANSACTION !!!
,I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowState(  907): WIN DEATH: Window{423c7748 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  907): Client connection lost with reason: 4
,I/dalvikvm-heap( 4132): Grow heap (frag case) to 15.213MB for 1821008-byte allocation
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1589): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1589): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
I/acms    ( 1888): Unregistering com.test.thalitest
D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,E/acms    ( 1888): Could not unregister removed application com.test.thalitest
,W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/VoicemailCleanupService( 1298): Cleaning up data for package: com.test.thalitest
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/PMS     (  907): acquireWL(4368d008): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1429 10028 null
,W/GeofencerStateMachine( 1429): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/Launcher( 1272): Deferring update until onResume
,D/Launcher( 1272): waitUntilResume // bindAppsRemoved
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,D/PackageBroadcastService( 1227): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/ActivityManager(  907): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4759 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/PMS     (  907): releaseWL(4368d008): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/ActivityManager(  907): Delaying start of: ServiceRecord{4261ccc0 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/MultiDex( 4759): install
,E/ExternalAccountType( 1330): Unsupported attribute readOnly
,I/MultiDex( 4759): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/ActivityManager(  907): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4775 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/MultiDex( 4759): loading existing secondary dex files
I/MultiDex( 4759): load found 1 secondary dex files
I/MultiDex( 4759): install done
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PeopleContactsSync( 1227): CP2 sync disabled
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1227, uid=10028, userID:0
,I/MultiDex( 4775): install
,I/MultiDex( 4775): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4775): loading existing secondary dex files
,I/MultiDex( 4775): load found 1 secondary dex files
,I/MultiDex( 4775): install done
,I/Icing   ( 1227): doRemovePackageData com.test.thalitest
D/PMS     (  907): acquireWL(43ea71b0): PARTIAL_WAKE_LOCK  Icing 0x1 1227 10028 null
,D/PMS     (  907): releaseWL(43ea71b0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ProviderInstaller( 4775): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ProviderInstaller( 4759): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  907): Killing 4364:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=4364
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 1397): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 1397): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Resuming delayed broadcast
,D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_REMOVED
,I/IcingCorporaProvider( 2892): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4797 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/ActivityManager(  907): Recipient 4364
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(41c1b6d8): PARTIAL_WAKE_LOCK  Icing 0x1 1227 10028 null
,I/IcingCorporaProvider( 2892): UpdateCorporaTask done [took 262 ms] updated apps [took 262 ms] 
,E/SQLiteLog( 4759): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 4759): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca5ea08
,E/DriveAsyncService( 4759): disk I/O error (code 3850)
E/DriveAsyncService( 4759): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4759): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4759): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4759): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4759): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4759): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4759): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4759): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4759): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4759): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4759): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4759): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4759): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 4759): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
,E/SQLiteDBG( 4759): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca5ea08
,E/DocListDatabase( 4759): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4759): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4759): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4759): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4759): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4759): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4759): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4759): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4759): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4759): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4759): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4759): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4759): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4759): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4759): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4759): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4759): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4759): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4759): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4759): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4759): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4759): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4759): threadid=1: thread exiting with uncaught exception (group=0x416fce30)
,E/ActivityManager(  907): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4759): FATAL EXCEPTION: main
E/AndroidRuntime( 4759): Process: com.google.android.gms.drive, PID: 4759
E/AndroidRuntime( 4759): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4759): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4759): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4759): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4759): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4759): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4759): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4759): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4759): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4759): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4759): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4759): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4759): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4759): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4759): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4759): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4759): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4759): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4759): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4759): 	... 10 more
,D/Process ( 4759): killProcess, pid=4759
,D/Process ( 4759): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  907): Recipient 4759
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Process com.google.android.gms.drive (pid 4759) has died.
,W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
,E/SQLiteDatabase( 4797): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
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
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4797): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4797): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4797): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4797): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4797): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4797): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4797): 	at fx.a(GellyInjectorStore.java:95),
E/SQLiteDatabase( 4797): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4797): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4797): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4797): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4797): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4797): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4797): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4797): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4797): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4797): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4797): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4797): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4797): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4797): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4797): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4797): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4797): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4797): Couldn't open ClientFlag.db for writing (will try read-only):,
E/SQLiteOpenHelper( 4797): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240),
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4797): ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4797): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4797): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263),
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4797): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4797): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4797): ,	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4797): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4797): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4797): 	at aGR.a(RuntimeProvider.java:116)
,E/SQLiteOpenHelper( 4797): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4797): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4797): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4797): 	at aGw.a(GellyInjector.java:117),
E/SQLiteOpenHelper( 4797): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4797): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4797): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4797): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924),
E/SQLiteOpenHelper( 4797): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4797): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4797): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4797): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4797): ,	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4797): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4797): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4797): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4797): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712),
E/SQLiteOpenHelper( 4797): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4797): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4797): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
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
E/SQLiteDatabase( 4797): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4797): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4797): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4797): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4797): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4797): threadid=11: thread exiting with uncaught exception (group=0x416fce30)
,E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4797): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4797): Process: com.google.android.apps.docs, PID: 4797
E/AndroidRuntime( 4797): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4797): 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4797): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4797): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4797): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4797): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4797): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4797): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4797): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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
,E/SQLiteDatabase( 4797): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
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
E/SQLiteDatabase( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4797): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4797): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4797): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4797): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4797): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4797): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4797): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4797): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4797): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4797): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4797): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4797): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4797): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4797): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4797): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4797): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4797): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4797): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4797): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4797): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4797): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4797): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4797): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4797): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4797): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4797): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4797): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4797): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4797): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4797): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4797): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4797): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4797): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4819 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/SQLiteOpenHelper( 4797): Opened ClientFlag.db in read-only mode
D/Process ( 4797): killProcess, pid=4797
D/Process ( 4797): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
W/PackageManager(  907): Unable to load service info ResolveInfo{41c535d0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41bbfee0 +
I/Prism.WidgetManager( 1272): onLoadItems() +
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4797
,I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4797) has died.
,W/ContextImpl( 4819): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4819): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4819): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4819): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4819): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4819): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4819): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4819): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4819): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4819): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4819): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4819): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4819): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4819): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4819): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4819): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4819): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4819): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4819): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4819): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4819): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4819): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4819): threadid=10: thread exiting with uncaught exception (group=0x416fce30)
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4832 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/AndroidRuntime( 4819): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4819): Process: com.android.keychain, PID: 4819
,E/AndroidRuntime( 4819): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4819): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4819): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4819): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4819): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4819): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4819): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4819): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4819): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4819): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4819): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4819): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4819): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4819): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4819): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4819): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4819): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4819): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4819): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4819): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  907): App crashed! Process: com.android.keychain
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4819): killProcess, pid=4819
,D/Process ( 4819): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453370752045.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  907): Recipient 4819
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Process com.android.keychain (pid 4819) has died.
,W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10585ms
D/AppTag  ( 4832): getInstance(Context context)
,D/AppTag  ( 4832): getInstance(Context context)
,D/AppTag  ( 4832): onCreate()
,D/PMS     (  907): acquireWL(432654c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4132 10160 null
,I/dalvikvm-heap( 4132): Grow heap (frag case) to 16.948MB for 1821008-byte allocation
D/PMS     (  907): releaseWL(432654c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4851 uid=10098 gids={50098, 3003, 5012}
,D/Process (  907): killProcessQuiet, pid=4448
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4448:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4448
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) },
,D/RemoteDisplayProvider(  907): start
,I/DeviceManagement( 4851): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4851 dbg=false s=true
,I/DeviceManagement( 4851): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4851): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4851): WorkflowService: Starting workflow service
,I/DeviceManagement( 4851): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b5fef8] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4851): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4851): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4851): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4851): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 4851): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4865 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 4851): SessionStateController: Checking invariants...
,W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,D/Documents( 4865): Loading roots for com.android.providers.downloads.documents
,D/Documents( 4865): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 4865): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
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
E/SQLiteDatabase( 4865): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4865): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4865): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4865): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4865): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4865): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4865): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4865): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4865): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4865): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4865): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4865): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4865): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4865): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4865): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4865): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4865): threadid=1: thread exiting with uncaught exception (group=0x416fce30)
,D/Process (  907): killProcessQuiet, pid=4588
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/AndroidRuntime( 4865): FATAL EXCEPTION: main
E/AndroidRuntime( 4865): Process: com.android.documentsui, PID: 4865
E/AndroidRuntime( 4865): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4865): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4865): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4865): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4865): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4865): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4865): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4865): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4865): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4865): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4865): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4865): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4865): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
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
E/AndroidRuntime( 4865): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4865): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4865): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4865): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4865): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4865): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4865): 	... 10 more
I/ActivityManager(  907): Killing 4588:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,E/ActivityManager(  907): App crashed! Process: com.android.documentsui
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453370752316.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  907): Recipient 4588
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
I/ActivityManager(  907): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4880 uid=10023 gids={50023, 1028, 1015, 1023}
D/Process ( 4865): killProcess, pid=4865
D/Process ( 4865): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/GCM     ( 1369): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  907): Recipient 4865
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  907): killProcessQuiet, pid=3874
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  907): Killing 3874:com.google.android.music:main/u0a154 (adj 15): empty #17
I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  907): Process com.android.documentsui (pid 4865) has died.
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Recipient 3874
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  907): Client com.google.android.music (pid 3874): Died!
D/GCM     ( 1369): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,D/ExternalStorage( 4880): After updating volumes, found 1 active roots
,E/SQLiteDatabase( 4851): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4851): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4851): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4851): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4851): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4851): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4851): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4851): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4851): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4851): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4851): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4851): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4851): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4851): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4851): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4851): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4851): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4851): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4851): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4851): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4851): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4895 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4851): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4851): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4851): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4851): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4851): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4851): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4851): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4851): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4851): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4851): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4851): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4851): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4851): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 4851): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b5fef8]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4851): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4851): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4851): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4851): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4851): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4851): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4851): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4851): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4851): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4851): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4851): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4851): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4851): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4851): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4851): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4851): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4851): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4851): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4851): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4851): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4851): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4851): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4851): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4851): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4851): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4851): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4851): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4851): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4851): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 4851): WorkflowService: Stopping workflow service
,W/asset   ( 1272): Copying FileAsset 0x5f62e228 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
E/Prism.WidgetManager( 1272): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1272): onLoadItems() -
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41bbfee0 -
E/SQLiteLog( 1272): (3850) statement aborts at 16: [DELETE FROM appscustomize WHERE _id=75] disk I/O error
E/SQLiteDBG( 1272): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.launcher/databases/launcher.db, handle = 0x5ca74dd0
W/dalvikvm( 1272): threadid=11: thread exiting with uncaught exception (group=0x416fce30)
E/ActivityManager(  907): App crashed! Process: com.htc.launcher
E/AndroidRuntime( 1272): FATAL EXCEPTION: TaskWorker
E/AndroidRuntime( 1272): Process: com.htc.launcher, PID: 1272
E/AndroidRuntime( 1272): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1272): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1272): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1272): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1272): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1272): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1272): 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:344)
E/AndroidRuntime( 1272): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 1272): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 1272): 	at com.htc.launcher.pageview.RearrangeDBHelper$3.run(RearrangeDBHelper.java:151)
E/AndroidRuntime( 1272): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/AndroidRuntime( 1272): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/AndroidRuntime( 1272): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1272): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1272): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
E/SQLiteDatabase( 4895): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 4895): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4895): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4895): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4895): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 4895): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 4895): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 4895): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 4895): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4895): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4895): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4895): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4895): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 4895): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4895): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4895): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4895): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 4895): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 4895): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 4895): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 4895): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4895): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4895): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4895): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  907):   Force finishing activity com.htc.launcher/.Launcher
,W/SQLiteOpenHelper( 4895): Opened MyDB.db in read-only mode
,D/Process ( 1272): killProcess, pid=1272
,D/Process ( 1272): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1453370752469.dbox_tmp: open failed: EROFS (Read-only file system)
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
,D/Process (  907): killProcessQuiet, pid=4505
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4505:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4505
,I/Icing   ( 1227): Indexing 3E78574859FB8ED28F43D3ECB139F4117F00AB29 from com.google.android.googlequicksearchbox
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1124516088
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
,I/ActivityManager(  907): START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from pid 0
E/ActivityManager(  907): handleTopAppChanged(): The first top app is died!?
E/ActivityManager(  907): android.os.TransactionTooLargeException
E/ActivityManager(  907): 	at android.os.BinderProxy.transact(Native Method)
E/ActivityManager(  907): 	at android.app.ApplicationThreadProxy.scheduleChangeTopApp(ApplicationThreadNative.java:1438)
E/ActivityManager(  907): 	at com.android.server.am.ActivityManagerService.handleTopAppChanged(ActivityManagerService.java:18115)
E/ActivityManager(  907): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:16836)
E/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1004)
E/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1159)
E/ActivityManager(  907): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1860)
E/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2265)
E/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2252)
E/ActivityManager(  907): 	at com.android.server.am.ActivityStack.startActivityLocked(ActivityStack.java:2119)
E/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.startActivityUncheckedLockedImpl(ActivityStackSupervisor.java:2006)
E/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.startActivityUncheckedLocked(ActivityStackSupervisor.java:1507)
E/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.startActivityLocked(ActivityStackSupervisor.java:1386)
E/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.startHomeActivity(ActivityStackSupervisor.java:670)
E/ActivityManager(  907): 	at com.android.server.am.ActivityManagerService.startHomeActivityLocked(ActivityManagerService.java:3192)
E/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.resumeHomeActivity(ActivityStackSupervisor.java:327)
E/ActivityManager(  907): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1440)
E/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2265)
E/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2252)
E/ActivityManager(  907): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:3966)
E/ActivityManager(  907): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:4128)
E/ActivityManager(  907): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1146)
E/ActivityManager(  907): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
E/ActivityManager(  907): 	at dalvik.system.NativeStart.run(Native Method)
E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
E/ActivityManager(  907): TransactionSize: scheduleLaunchActivity(), TransactionTooLargeException, data size = 1484, Intent = Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher }
W/ActivityManager(  907): Exception when starting activity com.htc.launcher/.Launcher
W/ActivityManager(  907): android.os.TransactionTooLargeException
W/ActivityManager(  907): 	at android.os.BinderProxy.transact(Native Method)
W/ActivityManager(  907): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:896)
W/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1062)
W/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1159)
W/ActivityManager(  907): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1860)
W/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2265)
W/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2252)
W/ActivityManager(  907): 	at com.android.server.am.ActivityStack.startActivityLocked(ActivityStack.java:2119)
W/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.startActivityUncheckedLockedImpl(ActivityStackSupervisor.java:2006)
W/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.startActivityUncheckedLocked(ActivityStackSupervisor.java:1507)
W/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.startActivityLocked(ActivityStackSupervisor.java:1386)
W/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.startHomeActivity(ActivityStackSupervisor.java:670)
W/ActivityManager(  907): 	at com.android.server.am.ActivityManagerService.startHomeActivityLocked(ActivityManagerService.java:3192)
W/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.resumeHomeActivity(ActivityStackSupervisor.java:327)
W/ActivityManager(  907): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1440)
W/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2265)
W/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2252)
W/ActivityManager(  907): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:3966)
W/ActivityManager(  907): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:4128)
W/ActivityManager(  907): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1146)
W/ActivityManager(  907): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/ActivityManager(  907): 	at dalvik.system.NativeStart.run(Native Method)
,E/Icing   ( 1227): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
,E/Icing   ( 1227): Could not init tag ds.tag.deleted
,I/ActivityManager(  907): Recipient 1272
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/InputDispatcher(  907): channel '42539d68 com.htc.launcher.Launcher (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  907): channel '42539d68 com.htc.launcher.Launcher (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  907): Attempted to unregister already unregistered input channel '42539d68 com.htc.launcher.Launcher (s)'
I/ActivityManager(  907): Process com.htc.launcher (pid 1272) has died.
I/WindowState(  907): WIN DEATH: Window{42539d68 u0 com.htc.launcher/com.htc.launcher.Launcher}
I/WindowManager(  907): WINDOW DIED Window{42539d68 u0 com.htc.launcher/com.htc.launcher.Launcher}

```
