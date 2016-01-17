#### Test 5615109319b4771_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system,
D/WIFI_ICON( 1116): WifiActivity: 1
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
--------- beginning of /dev/log/main
E/cutils-trace( 4369): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4369): ====startRecUseTime====
D/htc.customization.log.level( 4369):  is 
W/CustomizationLogLevel( 4369): Level value is invalid, use default level 2
D/CustomizationManager( 4369):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4369): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4369): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4369): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4369): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4369): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4369): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4369): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4369): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4369): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4369): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4369): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4369): Parsing tag category name = system
I/CustomizationCIDLoader( 4369): Parsing tag category name = application
I/CustomizationCIDLoader( 4369): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4369): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4369): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4369): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4369): Parsing tag category name = Settings
D/CustomizationManager( 4369):  Read CID file spent 0.088 (s)
D/CustomizationManager( 4369):  All configurations done spent 0.088 (s)
W/HtcNativeFlag( 4369): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4369): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4369): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4369): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  908): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  908): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4369
D/PMS     (  908): acquireHCC(429cb898): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 908 1000 null
D/PMS     (  908): acquireHCC(4254e890): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 908 1000 null
W/asset   (  908): Copying FileAsset 0x6db6cce0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  908): @test_code: getHtcIntentFlag: 0 obj: 1121204096
I/FeedHostManager( 1272): [onPause]
I/FeedProviderManager( 1272): onPause
I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bbc478
I/SocialFeedProvider( 1272): +onPause
I/SocialFeedProvider( 1272): -onPause
D/PMS     (  908): acquireWL(4238f770): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 908 1000 null
I/ActivityManager(  908): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4380 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1272): [trimMemory] 20
W/asset   ( 4380): Copying FileAsset 0x5c7d1440 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  908): acquireWL(423956d0): PARTIAL_WAKE_LOCK  Icing 0x1 2217 10028 null
D/PMS     (  908): releaseWL(423956d0): PARTIAL_WAKE_LOCK  Icing 0x1 null
V/WebViewChromiumFactoryProvider( 4380): Binding Chromium to main looper Looper (main, tid 1) {41a74eb8}
I/LibraryLoader( 4380): Expected native library version number "",actual native library version number ""
I/chromium( 4380): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4380): Initializing chromium process, renderers=0
D/PMS     (  908): acquireWL(41e4f220): PARTIAL_WAKE_LOCK  Icing 0x1 2217 10028 null
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  908): java.lang.Throwable: stack dump
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42d2cb60:true
D/BluetoothAdapter( 4380): 1101578248: getState(). Returning 12
D/PMS     (  908): acquireWL(41bc6cc8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  908): acquireWL(4419d780): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  908): releaseWL(4419d780): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/Adreno-EGL( 4380): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4380): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4380): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4380): Local Branch: 
I/Adreno-EGL( 4380): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4380): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4380):                  aa63bbd948f41d15fc72f585e
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 26
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 78
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  908):    returned true
D/PMS     (  908): releaseWL(41e4f220): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  908): acquireWL(42538350): PARTIAL_WAKE_LOCK  Icing 0x1 2217 10028 null
W/chromium( 4380): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4380): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4380): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4380): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4380): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4380): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4380): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4380): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4380): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4380): CordovaWebView is running on device made by: HTC
D/PMS     (  908): releaseWL(42538350): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/AwContents( 4380): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  908): Displayed com.test.thalitest/.MainActivity: +271ms
W/ResourceType( 4380): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4380): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41abd6b8, mServedView=org.apache.cordova.engine.SystemWebView{41a83320 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 4380): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  908): Disable input method client, pid=1272
,I/InputMethodManagerService(  908): Enable input method client, pid=4380
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  908): releaseWL(4238f770): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4380): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4380): JniHelper::setJavaVM(0x4154d048), pthread_self() = 1663356304
,D/JX-Cordova( 4380): jxcore cordova android initializing
,I/dalvikvm-heap( 4380): Grow heap (frag case) to 12.000MB for 42652-byte allocation
,I/dalvikvm-heap( 4380): Grow heap (frag case) to 12.077MB for 95956-byte allocation
,I/dalvikvm-heap( 4380): Grow heap (frag case) to 12.156MB for 143930-byte allocation
,I/dalvikvm-heap( 4380): Grow heap (frag case) to 12.271MB for 215890-byte allocation
,I/dalvikvm-heap( 4380): Grow heap (frag case) to 12.446MB for 323830-byte allocation
,I/dalvikvm-heap( 4380): Grow heap (frag case) to 12.718MB for 485740-byte allocation
,I/dalvikvm-heap( 4380): Grow heap (frag case) to 13.669MB for 1092904-byte allocation
,I/dalvikvm-heap( 4380): Grow heap (frag case) to 14.637MB for 1639352-byte allocation
,I/dalvikvm-heap( 4380): Grow heap (frag case) to 15.881MB for 2459024-byte allocation
,I/ActivityManager(  908): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4428 uid=10077 gids={50077}
,D/PMS     (  908): acquireWL(42447848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10077}
V/AlarmManager(  908): sending alarm PendingIntent{424642a0: PendingIntentRecord{4249d640 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453044821928, Int=60000
,D/PMS     (  908): releaseWL(42447848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4428): SMSBackupAgentService started
,D/SMSBackup( 4428): Checking restore status
D/SMSBackup( 4428): Restore complete
,D/SMSBackup( 4428): cancelCheckAlarm
,D/SMSBackup( 4428): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  908): killProcessQuiet, pid=4167
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4167:com.google.android.apps.genie.geniewidget/u0a106 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4167
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(4247d060): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1397 10028 null
,I/dalvikvm-heap( 4380): Grow heap (frag case) to 18.070MB for 3688532-byte allocation
D/PMS     (  908): acquireWL(42388de8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1397 10028 null
,D/PMS     (  908): releaseWL(4247d060): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  908): releaseWL(42388de8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/jxcore-log( 4380): Initializing JXcore engine
,W/jxcore-log( 4380): JXcore engine is ready
,W/CpuWake (  908): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  908): <<release mCpuPerf_Freq wakelock
D/PMS     (  908): releaseHCC(429cb898): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  908): releaseHCC(4254e890): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4380): Starting JXcore engine
,W/jxcore-log( 4380): Platform android
W/jxcore-log( 4380): 
,W/jxcore-log( 4380): Process ARCH arm
W/jxcore-log( 4380): 
,D/WIFI_ICON( 1116): WifiActivity: 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  908): acquireWL(42429d28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,D/WifiDataStallTracker(  908): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  908): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
V/AlarmManager(  908): sending alarm PendingIntent{423138a0: PendingIntentRecord{422e1de0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=103427, Int=0
,D/WifiDataStallTracker(  908): updateDataStallInfo: mDataStallTxRxSum={txSum=65 rxSum=52} preTxRxSum={txSum=62 rxSum=50}
D/WifiDataStallTracker(  908): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  908): onDataStallAlarm: tag=19506 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  908): startDataStallAlarm: tag=19507 delay=15s
D/PMS     (  908): releaseWL(42429d28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4380): JXcore Cordova bridge is ready!
I/jxcore-log( 4380): 
,W/jxcore-log( 4380): JXcore engine is started
,I/chromium( 4380): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4380): Toggling radios to true
I/jxcore-log( 4380): 
,D/BluetoothAdapter( 4380): enable(): BT is already enabled..!
,D/WifiManager( 4380): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
,W/HtcDLNAServiceManager(  908): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  908): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  908): Settings:Agentvalue: 2
W/Settings:Agent(  908): >> traceCallingStack()
,W/Settings:Agent(  908): Process.myPid(): 908
W/Settings:Agent(  908): Process.myTid(): 1100
D/WifiService(  908): New client listening to asynchronous messages
D/WifiService(  908): setWifiEnabled: true pid=4380, uid=10189
E/WifiService(  908): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  908): isSprintWifiRestricted(): false
I/WifiService(  908): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  908): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
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
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  908): 
W/Settings:Agent(  908): << traceCallingStack(): 5(ms)
D/WifiManager( 4380): disconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiNative-wlan0(  908): doBoolean: DISCONNECT
D/WifiManager( 4380): reconnect: Base Package Name=com.test.thalitest, uid=10189
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): TDLS: Tear down peers
I/wpa_supplicant( 1177): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4380): Radios toggled
I/jxcore-log( 4380): 
I/jxcore-log( 4380): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4380): 
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1177): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1177): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1177): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  908): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  908): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  908): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  908): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  908): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1177): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1177): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 1177): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1177): send_and_recv error -67 - cmd 12
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
D/Tethering(  908): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1177): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8aa4bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1177):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1177): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1177): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1177): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1177): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1177): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1177): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1177): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1177): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1177): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1177): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1177): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1177): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1177): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1177): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/Tethering(  908): interf,aceLinkStateChanged wlan0, false
D/WifiNative-wlan0(  908):    returned true
D/Tethering(  908): interfaceStatusChanged wlan0, false
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiPerfLock(  908): release()
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  908): PerfLock released for exiting ConnectedState
,D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): Power_Mode_Type mode = 0
I/wpa_supplicant( 1177): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  908):    returned true
,D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  908): [RunningState] Stop DHCP
D/ConnectivityService(  908): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  908): acquireWL(41ee05a0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 908 1000 null
D/WifiP2pService(  908): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  908): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  908): doBoolean: RECONNECT
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): Fast associate: Old scan results
I/wpa_supplicant( 1177): wpa_supplicant_scan enter
I/wpa_supplicant( 1177): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1177): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1177): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1177): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=19507 mDataStallAlarmIntent=PendingIntent{42328000: PendingIntentRecord{422e1de0 android broadcastIntent}}
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  908):    returned true
,D/WifiStateMachine(  908): Enter handleNetworkDisconnect
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/libc    (  908): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  908): Provision feature enable=false
D/ConnectivityService(  908): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): Power_Mode_Type mode = 0
I/wpa_supplicant( 1177): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 61
D/UsbnetStateTracker(  908): isAvailable+-
D/UsbnetStateTracker(  908): reconnect
,D/UsbnetStateTracker(  908): isAvailable+-
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  908):    returned true
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  908): default: reconnect()
,D/MDST    (  908): default: setTeardownRequested(false)
D/MDST    (  908): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  908): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1828/10178)
D/WISPrService( 3805): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3805): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  908): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/ConnectivityService(  908): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  908): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  908): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  908): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiService(  908): New client listening to asynchronous messages
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
,D/ConnectivityService(  908): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): handleConnectivityChange: resetting
D/ConnectivityService(  908): resetConnections(wlan0, 3)
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  908): acquireWL(424f2490): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1362 10028 null
,D/libc    (  364): [NET] entry_id:6   entry:0xb7de4858  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb7de4190  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb7de4298  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb7de4420  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb7de4730  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb7de3fe0  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb7de40f8  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb7de4348  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/WISPrService( 3805): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3805): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  908): flush DNS cache for net 1(wlan0)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1828/10178)
D/Nat464Xlat(  908): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  908): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  908): acquireWL(42401650): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  908): acquireWL(435b7990): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
D/ConnectivityService(  908): reportInetCondition for net -1, percentage: 0 by  (1362/10028)
I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
D/WirelessDisplayService(  908): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  908): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  908): startScan Pid: 908 Uid 1000
,D/WifiNative-wlan0(  908): doBoolean: SCAN
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  908):    returned false
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  908): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  908): releaseWL(424f2490): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/BatSI   (  908): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  908): releaseWL(42401650): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1362/10028)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/PMS     (  908): releaseWL(435b7990): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  908): mActiveDefaultNetwork: -1
,D/ConnectivityService(  908): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  908): releaseWL(41bc6cc8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/GpsLocationProvider(  908): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  908): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  908): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  908): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  908): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  908): bSetPropertyMultiRAB:false
D/Tethering(  908): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
D/CaptivePortalTracker(  908): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  908): NoActiveNetworkState
I/Tethering(  908): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  908): ipv4Default null
I/Tethering(  908): No IPv4 upstream interface, giving up.
,D/Tethering(  908): TetherMasterSM: InitialState processMessage what=3
I/AlarmManager(  908): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/PMS     (  908): acquireWL(42d1ce88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/PMS     (  908): releaseWL(42d1ce88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1397/10028)
D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/ConnectivityHelper( 1272): [onReceive] WIFI(1): DISCONNECTED
,I/NetworkMonitor( 3872): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4264/10100)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4264/10100)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.google.android.music (3872/10154)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1868/1000)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10075)
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1828/10178)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (2801/10021)
,I/ActivityManager(  908): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4452 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4452): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4452): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4452): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4452): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4452): Preparing secondary program dexes.
V/DexLibLoader( 4452): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4452): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4452): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4452): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4452): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4452): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4452): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4452): Dex already copied
D/OdexVerifier( 4452): Odex verification is skipped.
,V/DexLibLoader( 4452): Creating class loader
,V/DexLibLoader( 4452): Finished creating class loader
V/DexLibLoader( 4452): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4452): Dex already copied
D/OdexVerifier( 4452): Odex verification is skipped.
,V/DexLibLoader( 4452): Creating class loader,
V/DexLibLoader( 4452): Finished creating class loader
,V/DexLibLoader( 4452): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4452): Dex already copied
D/OdexVerifier( 4452): Odex verification is skipped.
,V/DexLibLoader( 4452): Creating class loader
,V/DexLibLoader( 4452): Finished creating class loader
V/DexLibLoader( 4452): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4452): Dex already copied
D/OdexVerifier( 4452): Odex verification is skipped.
,V/DexLibLoader( 4452): Creating class loader
,V/DexLibLoader( 4452): Finished creating class loader
,V/DexLibLoader( 4452): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4452): DexLibLoader.ensureDexLoaded took 15 ms
,W/dalvikvm( 4452): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4452): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4452): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4452): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4452): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4452): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4452): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/HABCtrl (  908): TPE algorithm. remove timeout.
,D/HABCtrl (  908): ALG=2, lsvalue=10(0th)->40(1th), last_level=-1, lValue=39->64
,D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1177): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-60
I/wpa_supplicant( 1177): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-61
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
D/wpa_supplicant( 1177): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1177): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1177): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1177): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): Selecting BSS from priority group 1
I/wpa_supplicant( 1177): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1177): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1177): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1177): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1177):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1177):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-60
I/wpa_supplicant( 1177): Start print parameters
I/wpa_supplicant( 1177): wpa_s->wpa_state is 3
I/wpa_supplicant( 1177): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1177): isConcurrentMode() is 0
I/wpa_supplicant( 1177): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1177): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1177): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1177): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1177): wpa_s->reassociate is 1
I/wpa_supplicant( 1177): wpa_s->is_screen_on 1
I/wpa_supplicant( 1177): wpa_s->ifname wlan0
I/wpa_supplicant( 1177): End print parameters
I/wpa_supplicant( 1177): selected network = 1
D/wpa_supplicant( 1177): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8aa64e8  current_ssid=0x0
D/wpa_supplicant( 1177): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1177): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1177): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1177): check if in concurrent case
,I/wpa_supplicant( 1177): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/wpa_supplicant( 1177): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1177): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1177): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1177): RSN: PMKSA cache search - network_ctx=0xb8aa64e8 try_opportunistic=0
D/wpa_supplicant( 1177): RSN: Search for BSSID c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 1177): RSN: No PMKSA cache entry found,
I/wpa_supplicant( 1177): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1177): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 1177): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1177): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1177): nl80211: Unsubscribe mgmt frames handle 0xb8aa5718 (mode change)
D/wpa_supplicant( 1177): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8aa5718
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8aa5718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8aa5718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8aa5718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8aa5718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8aa5718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8aa5718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8aa5718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8aa5718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8aa5718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8aa5718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Connect (ifindex=22),
D/wpa_supplicant( 1177):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1177):   * freq=2412
D/wpa_supplicant( 1177):   * Auth Type 0
D/wpa_supplicant( 1177):   * WPA Versions 0x2
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1177): nl80211: Connect request send successfully
D/wpa_supplicant( 1177): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
W/dalvikvm( 4452): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - portControl=Auto
,D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  908): doString: LIST_DONGLES
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  908): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1177): reply (489) for get BSS: id=0
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1177): freq=5220
I/wpa_supplicant( 1177): level=-48
I/wpa_supplicant( 1177): tsf=0000000105871383
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG7005g
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=1
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-60
I/wpa_supplicant( 1177): tsf=0000000105871396
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG700
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=2
I/wpa_supplicant( 1177): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1177): freq=2427
I/wpa_supplicant( 1177): level=-78
I/wpa_supplicant( 1177): tsf=0000000105871404
I/wpa_supplicant( 1177): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=Gonzos
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=3
I/wpa_supplicant( 1177): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-61
I/wpa_supplicant( 1177): tsf=0000000105871400
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1177): ssid=01ABC
I/wpa_supplicant( 1177): ####
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  908): getDiscoveryDongleList
,D/WifiStateMachine(  908): == begin of scan result ==
,D/WifiStateMachine(  908): == (4) end of scan result ==
,D/WirelessDisplayService(  908): getDiscoveryDongleList
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/WifiStateMachine(  908): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 105871383, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -60, frequency: 2412, timestamp: 105871396, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2427, timestamp: 105871404, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -61, frequency: 2412, timestamp: 105871400, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): add 4 to mScanResults
D/BatSI   (  908): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  908): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,W/dalvikvm( 4452): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1177): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1177): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1177): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1177): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1177): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1177): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1177): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1177): nl80211: Connect event
D/wpa_supplicant( 1177): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1177): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1177): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1177): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1177): Add randomness: count=10 entropy=4
I/wpa_supplicant( 1177): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1177): TDLS: Remove peers on association
D/wpa_supplicant( 1177): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1177): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1177): EAPOL: enable timer tick
D/wpa_supplicant( 1177): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1177): htc_wext_set_keepalive +
I/wpa_supplicant( 1177): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1177): getPrivFuncNum +	
I/wpa_supplicant( 1177): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1177): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1177): Get randomness: len=32 entropy=5
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  908): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  908): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  908): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  908): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  908): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  908): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  908): Enter handleAssociatedWithEvent
D/WifiStateMachine(  908): Associated
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  908): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  908): Exit handleAssociatedWithEvent
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  908): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
,D/Tethering(  908): interfaceStatusChanged wlan0, false
,D/Tethering(  908): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1177): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/Tethering(  908): interfaceLinkStateChanged wlan0, true
D/Tethering(  908): interfaceStatusChanged wlan0, true
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8aa59f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1177):    addr=c0:ff:d4:d3:aa:48
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  908): updateConnectedAP...
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1177): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1177): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f11b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1177):    broadcast key
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1177): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1177): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1177): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1177): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiStateMachine(  908): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1177): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1177): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1177): set send_ind_to_ndc = 0
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1177): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1177): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1177): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1177): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1177): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1177): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/WifiMonitor(  908): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1177): EAPOL authentication completed successfully
I/wpa_supplicant( 1177): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1177): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1177): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1177): nl80211: if_removed already cleared - ignore event
D/WifiApDatabaseHandler(  908): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  908): This record is existed, only update it...
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  908): interfaceLinkStateChanged wlan0, true
D/Tethering(  908): interfaceStatusChanged wlan0, true
D/,HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiApDatabaseHandler(  908): updateConnectedAP...
D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  908): updateConnectedAP...
D/WifiStateMachine(  908): fetchFrequency(), freq = 2412
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  908): WifiApDatabaseHandler, WiFi AP database Inserting ..
E/FbInjectorInitializer( 4452): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  908): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateMachine(  908): This record is existed, only update it...
D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  908): updateConnectedAP...
D/WISPrService( 3805): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3805): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  908): Provision feature enable=false
D/ConnectivityService(  908): mActiveDefaultNetwork: -1
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/DhcpStateMachine(  908): [StoppedState] Start DHCP
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/WifiStateMachine(  908): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  908): acquireWL(440c8320): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 908 1000 null
,D/WifiStateMachine(  908): handlePreDhcpSetup mBluetoothConnectionActive: false
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): Power_Mode_Type mode = 1
I/wpa_supplicant( 1177): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  908):    returned null
E/WifiStateMachine(  908): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  908): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  908):    returned null
D/WifiP2pService(  908): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424c3430 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424c3430 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
,W/fb4a(:<default>):StaticBindingVerifier( 4452): Verify
,D/WifiService(  908): New client listening to asynchronous messages
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4452): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4452): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4452): Grow heap (frag case) to 9.518MB for 73240-byte allocation
,D/Process (  908): killProcessQuiet, pid=3487
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 3487:com.android.defcontainer/u0a19 (adj 15): empty #17
,D/PMS     (  908): acquireWL(43ce4248): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2217 10028 null
,I/ActivityManager(  908): Recipient 3487
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(4415a000): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2217 10028 null
,D/PMS     (  908): releaseWL(43ce4248): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2217/10028)
,D/PMS     (  908): releaseWL(4415a000): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1362): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2217/10028)
,D/AutoSetting( 1482): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  908): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4481 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1482/10053)
,D/AutoSetting( 1482): Util - no network available!
,D/AutoSetting( 1482): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1482): service - mHandler: cancel location update
,D/AutoSetting( 1482): service -           changes count: 0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1482/10053)
,W/fb4a(:<default>):UserScope( 4452): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4452): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4452): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4481): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4481): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4481): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4481): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  908): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4495 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=4201
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 4201:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4481/10078)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4481/10078)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4481/10078)
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4452): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  908): Recipient 4201
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  908): Client connection lost with reason: 4
,E/dalvikvm( 4452): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4452): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4452): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4452): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4452): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4452): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4452): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4452): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4452): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4452): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4452): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4452): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4452): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4452): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4452): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4452): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4452): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4452): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
D/Process (  908): killProcessQuiet, pid=3854
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4512 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  908): Killing 3854:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/dalvikvm-heap( 4452): Grow heap (frag case) to 9.927MB for 39954-byte allocation
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4512): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4512): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4452): Grow heap (frag case) to 10.003MB for 79892-byte allocation
I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420c4bd0
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = CM36282 Light sensor
,W/GAV2    ( 4512): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420c4bd0, eanble = 0, strlen(mName) = 59
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423221d8
W/SensorService(  908): Listener[1] = com.htc.smartdim.sensor_eye@41fcddb8
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/PMS     (  908): Going to sleep due to screen timeout...
I/ActivityManager(  908): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  908): Couldn't get kernel wake lock stats
V/LightsService(  908): setLight #2: color=#0
D/qdlights(  908): set_light_buttons_func: on=0 brightness=0
V/LightsService(  908): setLight #0: color=#0
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4512): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4512): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  908): Recipient 3854
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/PMS     (  908): mWirelessDisplayManager is null
D/WirelessDisplayService(  908): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,I/dalvikvm-heap( 4452): Grow heap (frag case) to 10.043MB for 84664-byte allocation
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4512/10151)
,I/dalvikvm-heap( 4452): Grow heap (frag case) to 10.285MB for 75760-byte allocation
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
,W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44186a40 u0 ReceiverList{44185e68 4452 com.facebook.katana/10026/u0 remote:44178688}}
,W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44186a40 u0 ReceiverList{44185e68 4452 com.facebook.katana/10026/u0 remote:44178688}}
,W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{432b5238 u0 ReceiverList{432b51d8 4452 com.facebook.katana/10026/u0 remote:430fe618}}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
,D/PMS     (  908): acquireWL(43495848): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1397 10028 null
,D/PMS     (  908): releaseWL(43495848): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1397): Unknown pending intent to remove.
D/PMS     (  908): acquireWL(43dc5f60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1397 10028 null
D/PMS     (  908): releaseWL(43dc5f60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/SensorManager(  908): mEventCount = 900
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4452): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4452): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/wpa_supplicant( 1177): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1177): EAPOL: disable timer tick
,I/jxcore-log( 4380): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4380): 
,D/SurfaceControl(  908): Excessive delay in blankDisplay() while turning screen off: 373ms
D/NfcService( 1255): ScreenObserver: OFF
,D/NfcService( 1255): applyRouting - 0
V/KeyguardServiceDelegate(  908): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42583d40)
,D/NfcService( 1255): applyRouting -2
D/PMS     (  908): nativeSetInteractive:false
D/PMS     (  908): nativeSetInteractive:false done
D/PMS     (  908): nativeSetAutoSuspend:true
D/PMS     (  908): nativeSetAutoSuspend:true done
,D/HABCtrl (  908): TPE algorithm. remove timeout.
D/PMS     (  908): OOBE c monitor 11
I/InputMethodManagerService(  908): screenObserver, isScreenOn=false
I/InputMethodManagerService(  908): Disable input method client, pid=4380
D/PMS     (  908): acquireWL(430a9788): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMN     (  908): wakingUp
V/WebViewChromiumFactoryProvider( 4512): Binding Chromium to main looper Looper (main, tid 1) {41a7b148}
I/LibraryLoader( 4512): Expected native library version number "",actual native library version number ""
I/chromium( 4512): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4512): Initializing chromium process, renderers=0
,V/KeyguardServiceDelegate(  908): **** SHOWN CALLED ****
D/PMS     (  908): releaseWL(430a9788): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  908): No lock screen! windowToken=null
I/InputManager(  908): Cancel all due to getting PMS screen off broadcast
,D/WirelessDisplayService(  908): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,E/AudioManagerAndroid( 4512): BLUETOOTH permission is missing!
,D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMN     (  908): onScreenOn
D/PMS     (  908): acquireWL(43657698): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  908): acquireWL(4382d430): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  908): releaseWL(43657698): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  908): acquireWL(43e04708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
D/PMS     (  908): releaseWL(43e04708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/Adreno-EGL( 4512): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4512): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4512): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4512): Local Branch: 
I/Adreno-EGL( 4512): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4512): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4512):                  aa63bbd948f41d15fc72f585e
,D/MtpService( 2801): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2801): [MTP][onReceive]-
,D/NfcService( 1255): applyRouting - 0
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  908): updateBatteryInfo
D/DotMatrix( 1609): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1609): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1609): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NfcService( 1255): applyRouting -2
D/PMS     (  908): acquireWL(43cb3638): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_ON
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  908): releaseWL(43cb3638): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
D/AlarmManager(  908): ACTION_SCREEN_ON
I/AlarmManager(  908): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done recovering
I/AlarmManager(  908): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  908): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1177): Change stage from stage0 to stage3
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): SET_SCREEN_ON:On
I/wpa_supplicant( 1177): htc_wext_set_keepalive +
I/wpa_supplicant( 1177): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1177): getPrivFuncNum +	
I/wpa_supplicant( 1177): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  908):    returned true
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  908):    returned true
,I/NSApplication( 4512): Starting up...
,I/ClockThread( 1116): stop update clock
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4512/10151)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4512/10151)
W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
D/NetworkPolicy(  908): updateScreenOn: false
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3582/10160)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3582/10160)
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,D/Process (  908): killProcessQuiet, pid=4230
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 4230:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4230
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1828/10178)
,D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1828/10178)
D/GCM     ( 1362): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
D/DotMatrix( 1609): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/AutoSetting( 1482): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  908): acquireWL(42d3bbe8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1397 10028 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1801): onScreenOn: false
D/TetherSettings( 3805): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3805): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3805): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3805): Cust_ConnectToPC   : spcsc>false
D/        ( 3805): Cust_ConnectToPC   : IPT>true
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1801): onScreenOn: 1453044826765
D/        ( 3805): Cust_ConnectToPC   : Singel_USB>false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1801): onScreenOn: 1453044826765
W/Settings( 3805): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3805): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3805): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3805): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3805): onReceive:android.intent.action.USER_PRESENT
I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423221d8
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423221d8, eanble = 0, strlen(mName) = 91
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  908): Listener[0] = com.htc.smartdim.sensor_eye@41fcddb8
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/AutoSetting( 1482): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/PMS     (  908): releaseWL(42d3bbe8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/ContextImpl( 3805): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/PMN     (  908): goingToSleep
,I/SmartNS_PSService( 3805): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3805): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3805):  defaultType:0
D/PMS     (  908): acquireWL(43542400): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 908 1000 null
,D/AlarmManager(  908): ACTION_SCREEN_OFF
I/AlarmManager(  908): [AlarmQueuing] screen off now: 
I/AlarmManager(  908): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=19508 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): SET_SCREEN_ON:Off
I/wpa_supplicant( 1177): htc_wext_set_keepalive +
I/wpa_supplicant( 1177): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1177): getPrivFuncNum +	
I/wpa_supplicant( 1177): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1177): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1177): get_ip_address source addr = 02000000
I/AlarmManager(  908): [AlarmQueuing] wifi connection: true
D/PMS     (  908): acquireWL(43dccbe0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 908 1000 null
,D/PMS     (  908): releaseWL(43dccbe0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
I/wpa_supplicant( 1177): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1177): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  908):    returned true
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/NetworkPolicy(  908): updateScreenOn: false
,D/ContactMessageStore( 1243): start background delete task...
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4564 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/AutoSetting( 1482): service - mHandler: cancel location update
,D/DotMatrix( 1609): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/AutoSetting( 1482): service -           changes count: 0
,D/DotMatrix( 1609): [EventService] getTotalRam: 1873 Mb
W/ContextImpl( 4564): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1801): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1801): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1801): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1801): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1801): onScreenOff
D/PMS     (  908): acquireWL(43c87f60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1397 10028 null
D/PMS     (  908): releaseWL(43c87f60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/SmartSyncUtils( 4564): isEpsOn(), nState = 0
D/PMS     (  908): acquireWL(440ee238): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4564 1000 null
,D/PMS     (  908): releaseWL(440ee238): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4564): getMobilePolicyEnabled, result = true
,D/Process (  908): killProcessQuiet, pid=4264
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4264:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,W/ContextImpl( 4564): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  908): Recipient 4264
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/SmartSyncUtils( 4564): isEpsOn(), nState = 0
D/SmartSyncUtils( 4564): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4564): getMobilePolicyEnabled, result = true
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41fcddb8
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,D/WifiService(  908): New client listening to asynchronous messages
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 1
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41fcddb8, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 0
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41fcddb8, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41fcddb8
E/ActivityThread(  908): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424cbf18 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424cbf18 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/jxcore-log( 4380): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4380): 
,I/jxcore-log( 4380): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4380): 
,I/jxcore-log( 4380): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4380): 
,I/jxcore-log( 4380): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4380): 
,I/jxcore-log( 4380): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4380): 
,I/jxcore-log( 4380): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4380): 
,D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,W/ActivityManager(  908): Activity pause timeout for ActivityRecord{41c70510 u0 com.test.thalitest/.MainActivity t2}
,D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  908): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1177): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
D/WifiP2pService(  908): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  908): releaseWL(440c8320): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  908):    returned true
,D/WifiStateMachine(  908): gateway: /192.168.1.1
D/WifiNative-wlan0(  908): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1177): htc_wext_set_keepalive +
I/wpa_supplicant( 1177): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1177): getPrivFuncNum +	
I/wpa_supplicant( 1177): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1177): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1177): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1177): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  908): VerifyingLinkState enter
D/WifiStateMachine(  908): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  908): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  908): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  908): WAN detection
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  908): Provision feature enable=false
D/ConnectivityService(  908): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  908): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  908): default: teardown()
D/MDST    (  908): default: setTeardownRequested(true)
D/MDST    (  908): default: setEnableApn apnType =default , enable=false
V/NetworkPolicy(  908): mWifiStateReceiver: meteredHint=false,EPS mode=false
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/MDST    (  908): default: setTeardownRequested(true)
D/ConnectivityService(  908): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
E/ConnectivityService(  908): Unexpected mtu value: android.net.wifi.WifiStateTracker@42338b78
D/ConnectivityService(  908): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3805): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  908): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1828/10178)
,D/WifiStateMachine(  908): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  908): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  908): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  908): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  908): handleConnectivityChange: resetting
D/Nat464Xlat(  908): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  908): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WirelessDisplayService(  908): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  908):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
D/ConnectivityService(  908): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  908): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  908): acquireWL(441509d8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4481/10078)
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/PMS     (  908): acquireWL(43e0e178): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2217 10028 null
D/PMS     (  908): releaseWL(441509d8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  908): acquireWL(43de4be8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2217 10028 null
D/PMS     (  908): releaseWL(43e0e178): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2217/10028)
,I/CheckinService( 2217): Preparing to send checkin request
,I/EventLogService( 2217): Accumulating logs since 1453044769399
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 2217): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2217): Using GMS GoogleHttpClient
,D/ConnectivityService(  908): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  908): getNetworkInfo networkType=9 called by com.google.android.gms (2217/10028)
,D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.google.android.gms (2217/10028)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1362): GoogleAccountDataService.getToken()
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2217): awaiting user notification for token
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/DotMatrix( 1609): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1609): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41ac1a40 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 6 3 12
,I/ActivityManager(  908): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4619 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4619): install
,I/MultiDex( 4619): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/jxcore-log( 4380): Test app app.js loaded
I/jxcore-log( 4380): 
,I/Choreographer( 4380): Skipped 275 frames!  The application may be doing too much work on its main thread.
,I/MultiDex( 4619): loading existing secondary dex files
,I/MultiDex( 4619): load found 1 secondary dex files
,I/MultiDex( 4619): install done
,I/ProviderInstaller( 4619): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/chromium( 4380): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/ResourceType( 4380): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4380): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41a83320 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  908): releaseWL(43542400): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/Adreno-EGL( 4619): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4619): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4619): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4619): Local Branch: 
I/Adreno-EGL( 4619): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4619): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4619):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4619): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4619): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4619): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4619): Local Branch: 
I/Adreno-EGL( 4619): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4619): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4619):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  908): releaseWL(41ee05a0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  908): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  908): [AlarmQueuing] connectivity wifi: true
,V/Tethering(  908): bSetPropertyMultiRAB:false
,D/Tethering(  908): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/CaptivePortalTracker(  908): NoActiveNetworkState
I/acms    ( 1868): Checking Certificates
I/acms    ( 1868): Checking Developer Certificates
I/acms    ( 1868): Checking Application Certificates
I/acms    ( 1868): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
,I/acms    ( 1868): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1868): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1868): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1868): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1868): Updating next query delay: 75600000
I/mlserverapp( 1868): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1868): cancelACMSProgrammedChecks
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1868/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1828/10178)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.musicenhancer (3895/10051)
,I/Tethering(  908): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  908): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  908): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  908): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  908): Found interface wlan0
,D/Tethering(  908): TetherMasterSM: InitialState processMessage what=3
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [3][0][0]
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10075)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.google.android.music (3872/10154)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4481/10078)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1397/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
I/NetworkMonitor( 3872): type=WIFI subType= reason=null isConnected=true
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTED
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1397/10028)
D/PMS     (  908): acquireWL(424d5558): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(4244fba8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
,D/PMS     (  908): acquireWL(42d30ea8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 908 1000 WorkSource{10106}
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/GpsLocationProvider(  908): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  908): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  908): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  908): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  908): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4638 uid=10106 gids={50106, 3003, 5012}
D/PMS     (  908): releaseWL(4244fba8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  908): releaseWL(424d5558): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (2801/10021)
E/ExternalAccountType( 1332): Unsupported attribute readOnly
,D/PMS     (  908): acquireWL(423b59e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2217 10028 null
,D/PMS     (  908): releaseWL(423b59e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1362): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1362/10028)
D/PMS     (  908): acquireWL(44179808): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1362 10028 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2217/10028)
D/libc    ( 1362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1362): [NET] getaddrinfo-,err=8
D/libc    ( 1362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1362): [NET] getaddrinfo-, 1
D/libc    ( 1362): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =195 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,D/AutoSetting( 1482): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4481): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4481): onReceive CONNECTIVITY_CHANGE networkType=1
,I/Adreno-EGL( 4619): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4619): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4619): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4619): Local Branch: 
I/Adreno-EGL( 4619): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4619): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4619):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1482/10053)
,D/AutoSetting( 1482): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1482): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4512/10151)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1482/10053)
D/AutoSetting( 1482): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1482): service - onStartCommand() check timezone in 30000
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 243
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1362): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3582/10160)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3582/10160)
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1828/10178)
,W/fb4a(:<default>):UserScope( 4452): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4452): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/libc    ( 1362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1362): [NET] getaddrinfo-,err=8
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1362/10028)
D/PMS     (  908): acquireWL(43754980): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/PMS     (  908): releaseWL(43754980): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/NewsWeather( 4638): LocationClient connecting
,I/NewsWeather( 4638): NewsAccounts: 2, AllSystemAccounts 1.
,E/dalvikvm( 4638): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4638): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4638): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4638): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4638): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,W/Settings( 4619): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/fb4a(:<default>):LocalFbBroadcastManager( 4452): Called registerBroadcastReceiver twice.
,D/GCM     ( 1362): Connected
D/PMS     (  908): acquireWL(4313aa38): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1362 10028 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (4619/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1362/10028)
D/PMS     (  908): releaseWL(44179808): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1362/10028)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  908): handleInetConditionChange: starting a change hold
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1362/10028)
D/PMS     (  908): releaseWL(4313aa38): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  908): acquireWL(424eb2f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1362 10028 null
,I/ProviderInstaller( 4638): Installed default security provider GmsCore_OpenSSL
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(425f2618): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(425f2618): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1362/10028)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1362/10028)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
I/NewsWeather( 4638): Last usage 0, idle 1453044828s, sync interval 2592000s
,I/NewsWeather( 4638): setPeriodicSync in seconds 2592000
,D/GCM     ( 1362): Message class mpf
,I/CheckinTask( 2217): Sending checkin request (9013 bytes)
,I/NewsWeather( 4638): onConnected null
D/ConnectivityService(  908): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1362/10028)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  908): handleInetConditionChange: currently in hold - not setting new end evt
D/libc    ( 2217): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2217): [NET] getaddrinfo-,err=8
D/libc    ( 2217): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2217): [NET] getaddrinfo-, 1
,D/libc    ( 2217): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =e69f +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  908): releaseWL(424eb2f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  908): acquireWL(43658ba8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
D/PMS     (  908): acquireWL(4450c710): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1397 10028 null
,W/GCoreFlp( 1397): No location to return for getLastLocation()
,I/NewsWeather( 4638): LocationClient onConnected: location null
D/PMS     (  908): acquireWL(425a2e68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1397 10028 null
D/PMS     (  908): releaseWL(43658ba8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  908): releaseWL(4450c710): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4638): Skip sync for lookup editions
,I/NewsWeather( 4638): syncNewsAppData traffic type BACKGROUND_POLL
D/PMS     (  908): releaseWL(425a2e68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 264
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2217): [NET] getaddrinfo_proxy-, success
,I/NewsWeather( 4638): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
,W/GLSUser ( 1362): GoogleAccountDataService.getToken()
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4452/10026)
W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1609): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/DotMatrix( 1609): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 4638): Unrecoverable authentication exception
E/NewsWeather( 4638): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4638): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4638): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4638): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41c1b6e0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 4638): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4638): [NET] getaddrinfo-,err=8
D/libc    ( 4638): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
I/RemoteViews.Performance( 1116): com.google.android.gms 1 8 3 12
D/libc    ( 4638): [NET] getaddrinfo-, 1
D/libc    ( 4638): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =975c +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    ( 2217): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2217): [NET] getaddrinfo-,err=8
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=70
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4638): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4638): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4638): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  908): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=3 [31][1][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [1][0][0]
,D/PMS     (  908): acquireWL(43c8d600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
E/NewsWeather( 4638): Failed to syncNewsAppData
,E/NewsWeather( 4638): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  908): releaseWL(43c8d600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(4328e8b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/SyncManager(  908): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 67187, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  908): releaseWL(42d30ea8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/Process (  908): killProcessQuiet, pid=4284
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4284:com.htc.backup/1000 (adj 15): empty #17
D/PMS     (  908): releaseWL(4328e8b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1397/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(43df2360): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(43df2360): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 1471): service - handleMessage() stop self
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  908): Recipient 4284
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,D/PMS     (  908): acquireWL(431045e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
,D/PMS     (  908): releaseWL(431045e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1471): service - onDestroy() END
,D/AutoSetting( 1471): service - handleMessage() quit looper
,D/Process (  908): killProcessQuiet, pid=4250
,I/ActivityManager(  908): Killing 4250:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ConnectivityService(  908): getNetworkInfo networkType=9 called by com.google.android.gms (2217/10028)
,I/ActivityManager(  908): Recipient 4250
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.google.android.gms (2217/10028)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [1][0][0]
,W/GLSUser ( 1362): GoogleAccountDataService.getToken()
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PMS     (  908): releaseWL(4382d430): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/CheckinRequestBuilder( 2217): awaiting user notification for token
D/DotMatrix( 1609): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1609): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41c33198 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 3 11 3 12
,I/CheckinTask( 2217): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2217): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2217/10028)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2217/10028)
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  908): releaseWL(43de4be8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2217): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c61928 that was originally bound here
E/ActivityThread( 2217): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c61928 that was originally bound here
E/ActivityThread( 2217): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2217): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2217): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2217): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2217): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2217): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2217): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2217): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2217): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2217): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2217): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2217): 	at bks.a(SourceFile:298)
E/ActivityThread( 2217): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2217): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2217): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1362): GCM config loaded
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
D/libc    (  908): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =93bd +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  908): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  908): Find DNS Address www.htc.com/104.81.130.175
,I/GAV2    ( 4512): Thread[GAThread,5,main]: No campaign data found.
,D/WifiStateMachine(  908): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  908): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,I/GAV4    ( 4638): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  908): killProcessQuiet, pid=4308
,I/ActivityManager(  908): Killing 4308:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Recipient 4308
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  908): killProcessQuiet, pid=3895
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3895:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3895
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  908): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  908): acquireWL(440dc698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41a82188: PendingIntentRecord{41a82150 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=120437, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(440dc698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  908): acquireWL(44151480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/BatteryService(  908): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1609): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1609): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1609): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PMS     (  908): releaseWL(44151480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(4415f000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41cd8d30: PendingIntentRecord{424181b8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=132733, Int=0
,D/PMS     (  908): acquireWL(4415f2b8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 908 1000 null
,D/PMS     (  908): releaseWL(4415f000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(425b7560): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(4415f2b8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  908): releaseWL(425b7560): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 1482): service - mHandler: update timezone
,D/AutoSetting( 1471): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1482): service - handleMessage() stop self
,W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1471): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1471): service - onCreate()
W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1471): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1471): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/DotMatrix( 1609): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1609): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1471): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1471): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1471): service - mHandler: update timezone
,D/AutoSetting( 1482): service - handleMessage() quit looper
,D/AutoSetting( 1482): service - onDestroy() END
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1471): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1471): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1471): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1471): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1609): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1609): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41e2b7b8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 2 7 3 11
,D/PMS     (  908): acquireWL(432bb7a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10028}
,V/AlarmManager(  908): sending alarm PendingIntent{42265bd0: PendingIntentRecord{42109cb0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137392, Int=0
,D/GpsLocationProvider(  908): ALARM_XTRA_TIMEOUT
V/AlarmManager(  908): sending alarm PendingIntent{41fa3410: PendingIntentRecord{42456970 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140948, Int=0
D/PMS     (  908): acquireWL(43d3dce0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/PMS     (  908): releaseWL(432bb7a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1362/10028)
D/PMS     (  908): acquireWL(441b4ac8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
D/PMS     (  908): releaseWL(441b4ac8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  908): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b3b +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=243
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  908): [NET] getaddrinfo_proxy-, success
I/global  (  908): call createSocket() return a new socket.
D/libc    (  908): [NET] getaddrinfo+,hn 13(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  908): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  908): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  908): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  908):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  908): releaseWL(43d3dce0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{434e68d8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  908): acquireWL(42559170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41cd8d30: PendingIntentRecord{424181b8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=162749, Int=0
,D/PMS     (  908): acquireWL(43100790): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 908 1000 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(4259cd28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(42559170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=1 [55][1][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/PMS     (  908): acquireWL(43834920): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 908 1000 WorkSource{10106}
D/PMS     (  908): releaseWL(43100790): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  908): releaseWL(4259cd28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(4410fd48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(4410fd48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4638): Last usage 0, idle 1453044882s, sync interval 2592000s
I/NewsWeather( 4638): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4638): Skip sync for lookup editions
,I/NewsWeather( 4638): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4638): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1362): GoogleAccountDataService.getToken()
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1609): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1609): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,E/NewsWeather( 4638): Unrecoverable authentication exception
E/NewsWeather( 4638): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4638): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4638): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4638): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41e559d0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 12 4 12
,D/PMS     (  908): acquireWL(435fdbe0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
,D/PMS     (  908): releaseWL(435fdbe0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4638): Failed to syncNewsAppData
,E/NewsWeather( 4638): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(425a6c18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/SyncManager(  908): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 109923, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  908): releaseWL(43834920): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1397/10028)
,D/PMS     (  908): releaseWL(425a6c18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(43d0d0d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(43d0d0d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,D/PMS     (  908): acquireWL(432a1c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(432a1c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1609): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1609): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1609): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1471): service - handleMessage() stop self
,D/AutoSetting( 1471): service - onDestroy() END
,D/AutoSetting( 1471): service - handleMessage() quit looper
,D/Process (  908): killProcessQuiet, pid=4057
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4057:com.google.android.gm/u0a107 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 4057
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,D/PMS     (  908): acquireWL(42560a60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41a82188: PendingIntentRecord{41a82150 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=180438, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42560a60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(425b3a50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
I/BatteryService(  908): n_update end
D/PMS     (  908): releaseWL(425b3a50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1609): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1609): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1609): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  908): runPSCheck
,D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(4479ef00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41cd8d30: PendingIntentRecord{424181b8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=192799, Int=0
,D/PMS     (  908): acquireWL(441d22b8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 908 1000 null
D/PMS     (  908): releaseWL(4479ef00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(441cc368): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(441d22b8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  908): releaseWL(441cc368): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  908): acquireWL(43e0e178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10026}
,V/AlarmManager(  908): sending alarm PendingIntent{434e4588: PendingIntentRecord{425fa988 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=227101, Int=0
,I/ActivityManager(  908): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4694 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  908): sending alarm PendingIntent{41ccf0f0: PendingIntentRecord{425491d8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453044930987, Int=10800000
,D/PMS     (  908): releaseWL(43e0e178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.aurora (4694/10047)
,D/PMS     (  908): acquireWL(43d484c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10026}
,V/AlarmManager(  908): sending alarm PendingIntent{436a3298: PendingIntentRecord{425fa988 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=227232, Int=0
,D/PMS     (  908): releaseWL(43d484c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/Process (  908): killProcessQuiet, pid=4326
,I/ActivityManager(  908): Killing 4326:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Recipient 4326
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(43cbf7b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1609): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): releaseWL(43cbf7b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/DotMatrix( 1609): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1609): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(436bc688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10026}
,V/AlarmManager(  908): sending alarm PendingIntent{43144260: PendingIntentRecord{43cea3b8 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=227104, Int=120000
,V/AlarmManager(  908): sending alarm PendingIntent{41cd8d30: PendingIntentRecord{424181b8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=228501, Int=0
,D/PMS     (  908): acquireWL(436a5808): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 908 1000 null
D/PMS     (  908): releaseWL(436bc688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(43658d48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [21][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,D/PMS     (  908): acquireWL(43480d60): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 908 1000 WorkSource{10106}
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(436a5808): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  908): releaseWL(43658d48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(4347d540): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,I/NewsWeather( 4638): Last usage 0, idle 1453044948s, sync interval 2592000s
,I/NewsWeather( 4638): setPeriodicSync in seconds 2592000
D/PMS     (  908): releaseWL(4347d540): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4638): Skip sync for lookup editions
,I/NewsWeather( 4638): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4638): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1362): GoogleAccountDataService.getToken()
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/NewsWeather( 4638): Unrecoverable authentication exception
E/NewsWeather( 4638): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4638): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4638): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4638): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4638): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/DotMatrix( 1609): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1609): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41e57c00 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 10 3 12
,D/PMS     (  908): acquireWL(4217ead8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
,E/NewsWeather( 4638): Failed to syncNewsAppData
,E/NewsWeather( 4638): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/PMS     (  908): releaseWL(4217ead8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(41f52a58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/SyncManager(  908): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 163258, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  908): releaseWL(43480d60): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/PMS     (  908): releaseWL(41f52a58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1397/10028)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  908): acquireWL(42167758): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
D/PMS     (  908): releaseWL(42167758): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2217/10028)
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  908): acquireWL(41bb2690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41a82188: PendingIntentRecord{41a82150 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=240437, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(41bb2690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(43a61fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43a61fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1609): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1609): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1609): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  908): acquireWL(42406870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41cd8d30: PendingIntentRecord{424181b8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=258556, Int=0
,D/PMS     (  908): acquireWL(42366bc8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 908 1000 null
,D/PMS     (  908): releaseWL(42406870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(42d56768): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(42366bc8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  908): releaseWL(42d56768): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(41e39720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(41e39720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1609): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1609): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1609): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(422d6860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41a82188: PendingIntentRecord{41a82150 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=300437, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(422d6860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(4253cc70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
I/BatteryService(  908): n_update end
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1609): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1609): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1609): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): releaseWL(4253cc70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4380): --= Surplus to requirements =--
I/jxcore-log( 4380): 
I/jxcore-log( 4380): ****TEST TOOK:  ms ****
I/jxcore-log( 4380): 
,I/jxcore-log( 4380): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4380): 
,E/cutils-trace( 4721): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4721): ====startRecUseTime====
D/htc.customization.log.level( 4721):  is 
,W/CustomizationLogLevel( 4721): Level value is invalid, use default level 2
,D/CustomizationManager( 4721):  Read ACC file spent 0.098 (s)
D/CIDMapFileReader( 4721): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4721): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4721): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4721): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4721): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4721): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4721): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4721): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4721): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4721): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 4721): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4721): Parsing tag category name = system
I/CustomizationCIDLoader( 4721): Parsing tag category name = application
I/CustomizationCIDLoader( 4721): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4721): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4721): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 4721): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4721): Parsing tag category name = Settings
D/CustomizationManager( 4721):  Read CID file spent 0.152 (s)
,D/CustomizationManager( 4721):  All configurations done spent 0.152 (s)
,W/HtcNativeFlag( 4721): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4721): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4721): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4721): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  908): deletePackageAsUser: pkg=com.test.thalitest, pid=4721, uid=2000 user=0
,I/ActivityManager(  908): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
,D/Process (  908): killProcessQuiet, pid=4380
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  908): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  908): Killing 4380:com.test.thalitest/u0a189 (adj 0): stop com.test.thalitest
I/ActivityManager(  908):   Force finishing activity ActivityRecord{41c70510 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  908): Copying FileAsset 0x629cc1e8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  908): WIN DEATH: Window{41fcbe10 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  908): Client connection lost with reason: 4
,W/InputMethodManagerService(  908): Got RemoteException sending setActive(false) notification to pid 4380 uid 10189
,W/Binder  ( 1207): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1207): java.lang.NullPointerException
W/Binder  ( 1207): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1207): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1207): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1207): 	at dalvik.system.NativeStart.run(Native Method)
,I/ActivityManager(  908): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
,D/DotMatrix( 1609): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1609): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1609): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1868): Unregistering com.test.thalitest
,E/acms    ( 1868): Could not unregister removed application com.test.thalitest
,W/GeofencerStateMachine( 1397): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  908): acquireWL(4363c560): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1397 10028 null
D/PMS     (  908): releaseWL(4363c560): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
,I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/VoicemailCleanupService( 1298): Cleaning up data for package: com.test.thalitest
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
I/Launcher( 1272): Deferring update until onResume
,D/Launcher( 1272): waitUntilResume // bindAppsRemoved
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
,I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
D/PackageBroadcastService( 2217): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,I/ActivityManager(  908): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4736 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  908):   Scheme: "mms"
I/MultiDex( 4736): install
,I/MultiDex( 4736): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
I/ActivityManager(  908): Delaying start of: ServiceRecord{43d886a8 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/MultiDex( 4736): loading existing secondary dex files
I/MultiDex( 4736): load found 1 secondary dex files
I/MultiDex( 4736): install done
,D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/PeopleContactsSync( 2217): CP2 sync disabled
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2217, uid=10028, userID:0
,D/PMS     (  908): acquireWL(43da47c0): PARTIAL_WAKE_LOCK  Icing 0x1 2217 10028 null
I/Icing   ( 2217): doRemovePackageData com.test.thalitest
,D/PMS     (  908): releaseWL(43da47c0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  908): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4754 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/ProviderInstaller( 4736): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
,I/MultiDex( 4754): install
,I/MultiDex( 4754): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4754): loading existing secondary dex files
,I/MultiDex( 4754): load found 1 secondary dex files
,I/MultiDex( 4754): install done
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ProviderInstaller( 4754): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/[PluginManager]RegisterService( 1482): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 1482): handle notify Blinkfeed plugin client changed
I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=4340
,I/ActivityManager(  908): Killing 4340:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  908): Recipient 4340
,I/IcingCorporaProvider( 2973): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4774 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4736): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4736): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4736): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4736): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4736): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4736): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4736): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4736): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4736): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4736): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4736): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4736): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4736): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4736): 	at ctn.run(SourceFile:985)
,W/dalvikvm( 4736): threadid=12: thread exiting with uncaught exception (group=0x41645e30)
,E/ActivityManager(  908): App crashed! Process: com.google.android.gms.drive
,E/AndroidRuntime( 4736): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4736): Process: com.google.android.gms.drive, PID: 4736
E/AndroidRuntime( 4736): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4736): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4736): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4736): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4736): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4736): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4736): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4736): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4736): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4736): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4736): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4736): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4736): 	at ctn.run(SourceFile:985)
D/Process ( 4736): killProcess, pid=4736
,D/Process ( 4736): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/SQLiteLog( 2973): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2973): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63ce3088
W/dalvikvm( 2973): threadid=16: thread exiting with uncaught exception (group=0x41645e30)
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
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
E/ActivityManager(  908): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2973): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2973): Process: com.google.android.googlequicksearchbox:search, PID: 2973
E/AndroidRuntime( 2973): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2973): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2973): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2973): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2973): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2973): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2973): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2973): 	at cid.d(PG:186)
E/AndroidRuntime( 2973): 	at clo.g(PG:594)
E/AndroidRuntime( 2973): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2973): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2973): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2973): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2973): 	at clr.tL(PG:827)
E/AndroidRuntime( 2973): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2973): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2973): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2973): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2973): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2973): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2973): killProcess, pid=2973
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 2973): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
,W/PackageManager(  908): Unable to load service info ResolveInfo{425584c0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 4736
I/ActivityManager(  908): Process com.google.android.gms.drive (pid 4736) has died.
,W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 2973
D/MediaRouterService(  908): Client com.google.android.googlequicksearchbox (pid 2973): Died!
D/WifiService(  908): Client connection lost with reason: 4
,I/ActivityManager(  908): Process com.google.android.googlequicksearchbox:search (pid 2973) has died.
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
,W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
,D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  908): start
,W/AtomicFile(  908): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  908): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,E/SQLiteDatabase( 4774): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4774): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4774): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4774): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4774): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4774): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4774): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4774): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4774): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4774): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4774): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4774): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4774): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4774): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4774): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4774): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4774): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4774): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4774): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4774): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4774): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4774): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4774): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4774): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4774): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4774): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4774): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4774): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4774): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4774): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4774): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4774): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4774): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4774): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4774): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4774): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4774): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4774): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4774): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4774): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4774): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4774): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4774): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4774): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4774): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4774): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4774): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4774): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4774): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4774): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4774): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4774): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4774): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4774): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4774): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4774): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4774): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4774): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4774): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4774): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4774): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4774): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4774): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4774): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4774): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4774): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4774): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4774): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4774): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4774): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4774): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4774): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4774): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4774): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4774): threadid=11: thread exiting with uncaught exception (group=0x41645e30)
,E/ActivityManager(  908): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4774): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4774): Process: com.google.android.apps.docs, PID: 4774
E/AndroidRuntime( 4774): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4774): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4774): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4774): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4774): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4774): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4774): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4774): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4774): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4774): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4774): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4774): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4774): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4774): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4774): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4774): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4774): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  908): Can't write: system_app_crash
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
,D/Process ( 4774): killProcess, pid=4774
,D/Process ( 4774): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  908): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4792 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  908): Recipient 4774
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  908): killProcessQuiet, pid=4428
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 4428:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
I/ActivityManager(  908): Process com.google.android.apps.docs (pid 4774) has died.
,I/ActivityManager(  908): Recipient 4428
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4792): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4792): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4792): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4792): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4792): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4792): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4792): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4792): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4792): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4792): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4792): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4792): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4792): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4792): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4792): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4792): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4792): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4792): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4792): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4792): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4792): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4792): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4792): threadid=10: thread exiting with uncaught exception (group=0x41645e30),
I/ActivityManager(  908): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4805 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 4792): FATAL EXCEPTION: IntentService[KeyChainService],
E/AndroidRuntime( 4792): Process: com.android.keychain, PID: 4792
E/AndroidRuntime( 4792): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4792): 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4792): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4792): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4792): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4792): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4792): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4792): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4792): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4792): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4792): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4792): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4792): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4792): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4792): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4792): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4792): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4792): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4792): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4792): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  908): App crashed! Process: com.android.keychain
,D/ErrorReport(  908): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4792): killProcess, pid=4792
,E/ErrorReport(  908): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  908): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453045037913.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  908): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  908): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  908): 	... 4 more
D/Process ( 4792): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,D/AppTag  ( 4805): getInstance(Context context)
,I/ActivityManager(  908): Recipient 4792
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Process com.android.keychain (pid 4792) has died.
,W/ActivityManager(  908): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10518ms
,D/AppTag  ( 4805): getInstance(Context context)
,D/AppTag  ( 4805): onCreate()
,D/PMS     (  908): acquireWL(42306a18): PARTIAL_WAKE_LOCK  AsyncService 0x1 3582 10160 null
,D/PMS     (  908): releaseWL(42306a18): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  908): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4822 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 4822): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4822 dbg=false s=true
,I/DeviceManagement( 4822): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4822): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4822): WorkflowService: Starting workflow service
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41b0ad70 +
,I/Prism.WidgetManager( 1272): onLoadItems() +
I/DeviceManagement( 4822): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41aa9060] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4822): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4822): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4822): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4822): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  908): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4837 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 4822): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4822): SessionStateController: Checking invariants...
,D/Documents( 4837): Loading roots for com.android.providers.downloads.documents
,D/Documents( 4837): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4837): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4837): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4837): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4837): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4837): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4837): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4837): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4837): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4837): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4837): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4837): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4837): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4837): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4837): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4837): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4837): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4837): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4837): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4837): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4837): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4837): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4837): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4837): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4837): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4837): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4837): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4837): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4837): threadid=1: thread exiting with uncaught exception (group=0x41645e30)
E/AndroidRuntime( 4837): FATAL EXCEPTION: main
E/AndroidRuntime( 4837): Process: com.android.documentsui, PID: 4837
E/AndroidRuntime( 4837): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4837): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4837): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4837): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4837): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4837): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4837): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4837): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4837): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4837): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4837): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4837): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4837): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4837): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4837): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4837): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4837): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4837): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4837): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4837): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4837): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4837): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4837): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4837): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4837): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4837): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4837): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4837): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4837): 	... 10 more
,D/Process (  908): killProcessQuiet, pid=4564
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,E/ActivityManager(  908): App crashed! Process: com.android.documentsui
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  908): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4851 uid=10023 gids={50023, 1028, 1015, 1023}
I/ActivityManager(  908): Killing 4564:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/ErrorReport(  908): HtcErrorReportManager Begin---add error logs to dropbox
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 4564
,D/WifiService(  908): Client connection lost with reason: 4
,E/ErrorReport(  908): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  908): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453045038251.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  908): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  908): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  908): 	... 4 more
,D/Process (  908): killProcessQuiet, pid=3872
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  908): Killing 3872:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Process ( 4837): killProcess, pid=4837
,D/Process ( 4837): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  908): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/ActivityManager(  908): Recipient 4837
I/ActivityManager(  908): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Process com.android.documentsui (pid 4837) has died.
,I/ActivityManager(  908): Resuming delayed broadcast
D/ExternalStorage( 4851): After updating volumes, found 1 active roots
,E/SQLiteDatabase( 4822): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4822): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4822): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4822): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4822): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4822): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4822): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4822): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4822): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4822): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4822): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4822): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4822): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4822): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4822): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4822): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4822): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4822): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,I/DeviceManagement( 4822): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
I/ActivityManager(  908): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4867 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4822): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4822): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4822): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4822): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4822): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4822): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4822): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4822): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4822): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4822): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4822): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4822): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4822): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4822): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/DeviceManagement( 4822): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41aa9060]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4822): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4822): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4822): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4822): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4822): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4822): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4822): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4822): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4822): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4822): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4822): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4822): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4822): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4822): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4822): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4822): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4822): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4822): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4822): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4822): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4822): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4822): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4822): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4822): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4822): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4822): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4822): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4822): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4822): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4822): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4822): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4822): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4822): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/DeviceManagement( 4822): WorkflowService: Stopping workflow service
,D/MediaRouterService(  908): Client com.google.android.music (pid 3872): Died!
,I/ActivityManager(  908): Recipient 3872
,E/SQLiteDatabase( 4867): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 4867): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4867): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4867): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4867): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4867): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4867): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4867): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4867): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4867): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4867): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4867): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4867): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4867): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4867): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4867): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 4867): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 4867): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 4867): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 4867): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4867): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4867): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4867): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4867): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 4867): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4867): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4867): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4867): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4867): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4867): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4867): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4867): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4867): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4867): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4867): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4867): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4867): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4867): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4867): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 4867): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 4867): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 4867): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 4867): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4867): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4867): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4867): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/SQLiteOpenHelper( 4867): Opened MyDB.db in read-only mode
,D/Process (  908): killProcessQuiet, pid=4481

```
