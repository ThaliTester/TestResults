#### Test 50650278ec2c976_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1116): WifiActivity: 0
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,--------- beginning of /dev/log/main
E/cutils-trace( 4389): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4389): ====startRecUseTime====
D/htc.customization.log.level( 4389):  is 
W/CustomizationLogLevel( 4389): Level value is invalid, use default level 2
D/CustomizationManager( 4389):  Read ACC file spent 0.057 (s)
D/CIDMapFileReader( 4389): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4389): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4389): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4389): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4389): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4389): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4389): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4389): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4389): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4389): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4389): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4389): Parsing tag category name = system
I/CustomizationCIDLoader( 4389): Parsing tag category name = application
I/CustomizationCIDLoader( 4389): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4389): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4389): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4389): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4389): Parsing tag category name = Settings
D/CustomizationManager( 4389):  Read CID file spent 0.098 (s)
D/CustomizationManager( 4389):  All configurations done spent 0.099 (s)
W/HtcNativeFlag( 4389): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4389): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4389): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4389): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
D/PMS     (  905): acquireHCC(42a59fc8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4389
D/PMS     (  905): acquireHCC(42a14680): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
W/asset   (  905): Copying FileAsset 0x632109e0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1118235768
I/FeedHostManager( 1268): [onPause]
I/FeedProviderManager( 1268): onPause
I/FeedHostManager( 1268): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@421c7e60
D/PMS     (  905): acquireWL(42928b18): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/SocialFeedProvider( 1268): +onPause
I/SocialFeedProvider( 1268): -onPause
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4400 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
I/TrimMemoryManager( 1268): [trimMemory] 20
W/asset   ( 4400): Copying FileAsset 0x5c6ff420 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4400): Binding Chromium to main looper Looper (main, tid 1) {4208ae88}
I/LibraryLoader( 4400): Expected native library version number "",actual native library version number ""
I/chromium( 4400): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4400): Initializing chromium process, renderers=0
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42ab3748:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  905): acquireWL(42caf5c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  905): acquireWL(42b3bf78): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  905): releaseWL(42caf5c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4400): 1107955712: getState(). Returning 12
I/Adreno-EGL( 4400): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4400): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4400): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4400): Local Branch: 
I/Adreno-EGL( 4400): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4400): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4400):                  aa63bbd948f41d15fc72f585e
W/chromium( 4400): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4400): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4400): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4400): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4400): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4400): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4400): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4400): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4400): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4400): CordovaWebView is running on device made by: HTC
,W/AwContents( 4400): nativeOnDraw failed; clearing to background color.
D/WIFI_ICON( 1116): WifiActivity: 1
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/InputMethodManagerService(  905): Disable input method client, pid=1268
W/ResourceType( 4400): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4400): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@420d26b0, mServedView=org.apache.cordova.engine.SystemWebView{42098318 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  905): Enable input method client, pid=4400
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4400): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +297ms
D/PMS     (  905): releaseWL(42928b18): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4400): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4400): JniHelper::setJavaVM(0x41c48010), pthread_self() = 1662066496
D/JX-Cordova( 4400): jxcore cordova android initializing
W/dalvikvm( 4400): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 4400): Grow heap (frag case) to 11.640MB for 144892-byte allocation
,I/dalvikvm-heap( 4400): Grow heap (frag case) to 11.755MB for 217334-byte allocation
,I/dalvikvm-heap( 4400): Grow heap (frag case) to 11.930MB for 325996-byte allocation
,I/dalvikvm-heap( 4400): Grow heap (frag case) to 12.206MB for 488990-byte allocation
,D/PMS     (  905): acquireWL(42adee60): PARTIAL_WAKE_LOCK  Icing 0x1 2251 10028 null
,I/dalvikvm-heap( 4400): Grow heap (frag case) to 12.611MB for 733480-byte allocation
,D/PMS     (  905): releaseWL(42adee60): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(43f32030): PARTIAL_WAKE_LOCK  Icing 0x1 2251 10028 null
,D/PMS     (  905): releaseWL(43f32030): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(42b26678): PARTIAL_WAKE_LOCK  Icing 0x1 2251 10028 null
,D/PMS     (  905): releaseWL(42b26678): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(42870568): PARTIAL_WAKE_LOCK  Icing 0x1 2251 10028 null
,D/PMS     (  905): releaseWL(42870568): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/dalvikvm-heap( 4400): Grow heap (frag case) to 14.122MB for 1650320-byte allocation
,I/dalvikvm-heap( 4400): Grow heap (frag case) to 15.477MB for 2475476-byte allocation
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(42a59fc8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(42a14680): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4400): Grow heap (frag case) to 17.494MB for 3713210-byte allocation
,W/jxcore-log( 4400): Initializing JXcore engine
,W/jxcore-log( 4400): JXcore engine is ready
,W/jxcore-log( 4400): Starting JXcore engine
,W/jxcore-log( 4400): Platform android
W/jxcore-log( 4400): 
,W/jxcore-log( 4400): Process ARCH arm
W/jxcore-log( 4400): 
,I/jxcore-log( 4400): JXcore Cordova bridge is ready!
I/jxcore-log( 4400): 
,W/jxcore-log( 4400): JXcore engine is started
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,I/chromium( 4400): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4448 uid=10077 gids={50077}
,D/PMS     (  905): acquireWL(44611dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10077}
V/AlarmManager(  905): sending alarm PendingIntent{4208b4a0: PendingIntentRecord{42462728 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450109366111, Int=60000
,D/PMS     (  905): releaseWL(44611dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4448): SMSBackupAgentService started
,D/SMSBackup( 4448): Checking restore status
,D/SMSBackup( 4448): Restore complete
,D/SMSBackup( 4448): cancelCheckAlarm
,D/SMSBackup( 4448): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  905): killProcessQuiet, pid=3430
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  905): releaseWL(42b3bf78): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/ActivityManager(  905): Killing 3430:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3430
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(42a5bbc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
D/WifiDataStallTracker(  905): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  905): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  905): updateDataStallInfo: mDataStallTxRxSum={txSum=100 rxSum=83} preTxRxSum={txSum=99 rxSum=82}
D/WifiDataStallTracker(  905): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  905): onDataStallAlarm: tag=20439 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=20440 delay=15s
V/AlarmManager(  905): sending alarm PendingIntent{42944f08: PendingIntentRecord{42b20308 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105759, Int=0
D/PMS     (  905): releaseWL(42a5bbc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4400): Toggling radios to true
I/jxcore-log( 4400): 
,D/BluetoothAdapter( 4400): enable(): BT is already enabled..!
,D/WifiManager( 4400): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1716
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
,W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
W/Settings:Agent(  905): << traceCallingStack(): 1(ms)
,D/WifiManager( 4400): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  905): doBoolean: DISCONNECT
D/WifiManager( 4400): reconnect: Base Package Name=com.test.thalitest, uid=10348
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): TDLS: Tear down peers
,I/wpa_supplicant( 1177): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4400): Radios toggled
I/jxcore-log( 4400): 
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4400): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4400): 
D/WifiService(  905): setWifiEnabled: true pid=4400, uid=10348
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,D/WifiService(  905): New client listening to asynchronous messages
I/jxcore-log( 4400): Perf Test app loaded loaded
I/jxcore-log( 4400): 
I/Choreographer( 4400): Skipped 76 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4400): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 4400): check test folder
I/jxcore-log( 4400): 
,I/jxcore-log( 4400): found test : ./testFindPeers.js
I/jxcore-log( 4400): 
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1177): Clean 'force_connect' when disconnect
,I/wpa_supplicant( 1177): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1177): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3
,D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1177): TDLS: Remove peers on disassociation
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1177): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1177): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1177): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 1177): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb87acbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
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
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiNative-wlan0(  905):    returned true
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiPerfLock(  905): release()
D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  905): doBo,olean: DRIVER POWERMODE 0
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  905): acquireWL(4366abc8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): Power_Mode_Type mode = 0
I/wpa_supplicant( 1177): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 61
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/DhcpStateMachine(  905): [RunningState] Stop DHCP
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4,
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  905): doBoolean: RECONNECT
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): Fast associate: Old scan results
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1177): wpa_supplicant_scan enter
I/wpa_supplicant( 1177): State: DISCONNECTED -> SCANNING
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
I/wpa_supplicant( 1177): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1177): wpa_supplicant_trigger_scan +
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 33
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 1177): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1177): nl80211: Event message available
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1177): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  905):    returned true
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiStateMachine(  905): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20440 mDataStallAlarmIntent=PendingIntent{4293f038: PendingIntentRecord{42b20308 android broadcastIntent}}
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1868/10178)
,D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): Power_Mode_Type mode = 0
I/wpa_supplicant( 1177): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
D/UsbnetStateTracker(  905): isAvailable+-
D/UsbnetStateTracker(  905): reconnect
,D/UsbnetStateTracker(  905): isAvailable+-
,I/jxcore-log( 4400): found test : ./testSendData.js
I/jxcore-log( 4400): 
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WISPrService( 4141): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  905): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3,
D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 4141): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiService(  905): New client listening to asynchronous messages
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/ConnectivityService(  905): resetConnections(wlan0, 3)
D/libc    (  363): [NET] entry_id:3   entry:0xb73621d0  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb7361d90  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb7362320  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb7362818  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb7362108  removed 
D/libc    (  363): [NET] entry_id:8   entry:0xb73626f0  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb7361fd8  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb7362410  removed 
D/libc    (  363): [NET] entry_id:9   entry:0xb73625a0  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WISPrService( 4141): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4141): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,I//system/bin/ip(  363): RTNETLINK answers: No such process
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  905): acquireWL(425044b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1868/10178)
,D/PMS     (  905): acquireWL(431abe38): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10028)
,D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (1365/10028)
D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
,D/WifiNative-wlan0(  905): doBoolean: SCAN
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  905):    returned false
D/BatSI   (  905): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  905): acquireWL(43132190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
D/PMS     (  905): releaseWL(425044b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10028)
D/PMS     (  905): releaseWL(43132190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,D/PMS     (  905): releaseWL(431abe38): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43d3cd30): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
,D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  905): NoActiveNetworkState
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): releaseWL(43d3cd30): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1868/10178)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1895/1000)
,I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  905): ipv4Default null
I/Tethering(  905): No IPv4 upstream interface, giving up.
I/ConnectivityHelper( 1268): [onReceive] WIFI(1): DISCONNECTED
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 3865): type=WIFI subType= reason=null isConnected=false
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1268/10075)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1424/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4288/10100)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3865/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4288/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2475/10021)
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4470 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4470): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4470): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4470): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4470): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4470): Preparing secondary program dexes.
V/DexLibLoader( 4470): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4470): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4470): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
,V/DexLibLoader( 4470): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4470): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4470): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4470): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4470): Dex already copied
D/OdexVerifier( 4470): Odex verification is skipped.
,V/DexLibLoader( 4470): Creating class loader
,V/DexLibLoader( 4470): Finished creating class loader
V/DexLibLoader( 4470): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4470): Dex already copied
D/OdexVerifier( 4470): Odex verification is skipped.
,V/DexLibLoader( 4470): Creating class loader
,V/DexLibLoader( 4470): Finished creating class loader
V/DexLibLoader( 4470): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4470): Dex already copied
D/OdexVerifier( 4470): Odex verification is skipped.
,V/DexLibLoader( 4470): Creating class loader
,V/DexLibLoader( 4470): Finished creating class loader
V/DexLibLoader( 4470): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 4470): Dex already copied
D/OdexVerifier( 4470): Odex verification is skipped.
,V/DexLibLoader( 4470): Creating class loader
,V/DexLibLoader( 4470): Finished creating class loader
,V/DexLibLoader( 4470): Verifying classes from secondary dexes.
,D/DexLibLoader( 4470): DexLibLoader.ensureDexLoaded took 21 ms
,W/dalvikvm( 4470): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4470): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4470): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4470): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4470): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4470): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4470): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4470): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4470): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1177): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1177): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
I/wpa_supplicant( 1177): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-83
I/wpa_supplicant( 1177): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-86
I/wpa_supplicant( 1177): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-86
I/wpa_supplicant( 1177): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1177): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1177): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1177): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1177): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1177): Add randomness: count=11 entropy=4
D/wpa_supplicant( 1177): Add randomness: count=12 entropy=5
D/wpa_supplicant( 1177): Add randomness: count=13 entropy=6
D/wpa_supplicant( 1177): Add randomness: count=14 entropy=7
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=1 len=6
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
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1177): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): Selecting BSS from priority group 1
I/wpa_supplicant( 1177): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1177): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1177): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rs,n_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1177): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1177):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1177):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
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
D/wpa_supplicant( 1177): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb87ae4e8  current_ssid=0x0
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1177): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1177): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1177): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1177): check if in concurrent case
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
I/wpa_supplicant( 1177): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1177): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1177): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1177): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1177): RSN: PMKSA cache search - network_ctx=0xb87ae4e8 try_opportunistic=0
D/wpa_supplicant( 1177): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1177): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1177): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1177): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1177): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1177): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1177): nl80211: Unsubscribe mgmt frames handle 0xb87ad718 (mode change)
D/wpa_supplicant( 1177): nl80211: Subscribe to mgmt frames with non-AP handle 0xb87ad718
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb87ad718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb87ad718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb87ad718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb87ad718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb87ad718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb87ad718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb87ad718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb87ad718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb87ad718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb87ad718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1177):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1177):   * freq=2412
D/wpa_supplicant( 1177):   * Auth Type 0
D/wpa_supplicant( 1177):   * WPA Versions 0x2
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1177): nl80211: Connect request send successfully
D/wpa_supplicant( 1177): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1177): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,D/WirelessDisplayService(  905): getDiscoveryDongleList
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000),
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1177): reply (1068) for get BSS: id=0
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1177): freq=5220
I/wpa_supplicant( 1177): level=-49
I/wpa_supplicant( 1177): tsf=0000000108741405
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG7005g
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=1
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-48
I/wpa_supplicant( 1177): tsf=0000000108741427
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG700
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=2
I/wpa_supplicant( 1177): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1177): freq=2427
I/wpa_supplicant( 1177): level=-81
I/wpa_supplicant( 1177): tsf=0000000108741431
I/wpa_supplicant( 1177): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=Gonzos
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=3
I/wpa_supplicant( 1177): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1177): freq=2462
I/wpa_supplicant( 1177): level=-86
I/wpa_supplicant( 1177): tsf=0000000108741439
I/wpa_supplicant( 1177): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1177): ssid=UPC Wi-Free
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=4
I/wpa_supplicant( 1177): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-48
I/wpa_supplicant( 1177): tsf=0000000108741421
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1177): ssid=01ABC
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=5
I/wpa_supplicant( 1177): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1177): freq=2437
I/wpa_supplicant( 1177): level=-83
I/wpa_supplicant( 1177): tsf=0000000108741435
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1177): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=6
I/wpa_supplicant( 1177): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1177): freq=2462
I/wpa_supplicant( 1177): level=-86
I/wpa_supplicant( 1177): tsf=0000000108741443
I/wpa_supplicant( 1177): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=UPC5999698
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=7
,I/wpa_supplicant( 1177): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1177): freq=2437
I/wpa_supplicant( 1177): level=-91
I/wpa_supplicant( 1177): tsf=0000000108741448
I/wpa_supplicant( 1177): flags=
,E/FbInjectorInitializer( 4470): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (8) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 108741405, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 108741427, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2427, timestamp: 108741431, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -86, frequency: 2462, timestamp: 108741439, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -48, frequency: 2412, timestamp: 108741421, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -83, frequency: 2437, timestamp: 108741435, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2462, timestamp: 108741443, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 7: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 108741448, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 8 to mScanResults
D/BatSI   (  905): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/wpa_supplicant( 1177): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1177): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1177): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1177): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1177): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1177): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1177): nl80211: if_removed already cleared - ignore event
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
D/wpa_supplicant( 1177): Add randomness: count=15 entropy=8
I/wpa_supplicant( 1177): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1177): TDLS: Remove peers on association
D/wpa_supplicant( 1177): EAPOL: External notification - portEnabled=0
D/Tethering(  905): interfaceStatusChanged wlan0, false
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
D/Tethering(  905): [isWifi] getHotspotEnabled: false
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
D/wpa_supplicant( 1177): Get randomness: len=32 entropy=9
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString As,sociated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/WifiStateMachine(  905): Associated
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
D/WifiStateMachine(  905): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
I/wpa_supplicant( 1177): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb87ad9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1177):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1177): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1177): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ee9b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1177):    broadcast key
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1177): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1177): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1177): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1177): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1177): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1177): set send_ind_to_ndc = 0
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1177): EAPOL: External notification - portValid=1
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1177): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1177): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1177): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1177): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1177): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1177): EAPOL authentication completed successfully
I/wpa_supplicant( 1177): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1177): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1177): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1177): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
W/fb4a(:<default>):StaticBindingVerifier( 4470): Verify
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WISPrService( 4141): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/WISPrService( 4141): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/DhcpStateMachine(  905): [StoppedState] Start DHCP
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): Power_Mode_Type mode = 1
I/wpa_supplicant( 1177): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  905):    returned null
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(42ad1258): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4214f710 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4214f710 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4470): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4470): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4470): Grow heap (frag case) to 9.518MB for 73240-byte allocation
,D/Process (  905): killProcessQuiet, pid=4224
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4224:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/PMS     (  905): acquireWL(43680dd8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2251 10028 null
,I/ActivityManager(  905): Recipient 4224
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,D/PMS     (  905): acquireWL(43bb4a10): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2251 10028 null
,D/PMS     (  905): releaseWL(43680dd8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/PMS     (  905): releaseWL(43bb4a10): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1365): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/AutoSetting( 1388): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4499 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1388/10053)
,D/AutoSetting( 1388): Util - no network available!
,D/AutoSetting( 1388): service - onCreate()
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1388/10053)
,D/AutoSetting( 1388): service - AddressCache: using context: com.htc.Weather
,D/LocationManagerService(  905): request 428fad28 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1388): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1388): service - mHandler: cancel location update
,D/AutoSetting( 1388): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4470): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4470): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4470): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4499): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4499): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4499): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4499): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4515 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4499/10078)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4499/10078)
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4499/10078)
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4470): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4532 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=3846
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3846:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/dalvikvm-heap( 4470): Grow heap (frag case) to 9.967MB for 84664-byte allocation
,E/dalvikvm( 4470): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4470): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4532): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4532): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4470): Grow heap (frag case) to 9.982MB for 28144-byte allocation
,E/dalvikvm( 4470): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4470): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4470): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4470): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4470): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4470): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4470): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4470): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4470): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/GAV2    ( 4532): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/dalvikvm( 4470): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4470): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4470): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4470): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4470): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4470): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/dalvikvm( 4470): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,W/ContextImpl( 4532): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4532): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3846
,I/dalvikvm-heap( 4470): Grow heap (frag case) to 10.048MB for 39954-byte allocation
,I/dalvikvm-heap( 4470): Grow heap (frag case) to 10.125MB for 79892-byte allocation
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4532/10151)
,V/WebViewChromiumFactoryProvider( 4532): Binding Chromium to main looper Looper (main, tid 1) {420903c0}
,I/LibraryLoader( 4532): Expected native library version number "",actual native library version number ""
,I/chromium( 4532): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4532): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4532): BLUETOOTH permission is missing!
D/PMS     (  905): acquireWL(43c7f978): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  905): acquireWL(43d05f50): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  905): releaseWL(43d05f50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4532): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4532): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4532): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4532): Local Branch: 
I/Adreno-EGL( 4532): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4532): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4532):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4532): Starting up...
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4532/10151)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4532/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4121/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4121/10160)
,D/Process (  905): killProcessQuiet, pid=3967
,I/ActivityManager(  905): Killing 3967:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/dalvikvm-heap( 4470): Grow heap (frag case) to 10.289MB for 75760-byte allocation
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1868/10178)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1868/10178)
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 3967
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43d66708 u0 ReceiverList{43d34a78 4470 com.facebook.katana/10026/u0 remote:43d1bfd0}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43d66708 u0 ReceiverList{43d34a78 4470 com.facebook.katana/10026/u0 remote:43d1bfd0}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{441175c0 u0 ReceiverList{440ac818 4470 com.facebook.katana/10026/u0 remote:4407acf0}}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/PMS     (  905): acquireWL(441ebba8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1424 10028 null
,D/PMS     (  905): releaseWL(441ebba8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1424): Unknown pending intent to remove.
D/PMS     (  905): acquireWL(43820438): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1424 10028 null
D/PMS     (  905): releaseWL(43820438): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4470): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4470): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/wpa_supplicant( 1177): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1177): EAPOL: disable timer tick
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1177): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(42ad1258): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): gateway: /192.168.1.1
D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -48, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=20442 delay=15s
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiWatchdogStateMachine(  905): WAN detection
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1868/10178)
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
D/MDST    (  905): default: setEnableApn apnType =default , enable=false
,D/WISPrService( 4141): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1116): WifiActivity: 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@429b3f50
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
,D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  905): acquireWL(43783a08): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4499/10078)
I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:1
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(42b29cf0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2251 10028 null
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
D/PMS     (  905): acquireWL(4308b328): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2251 10028 null
D/PMS     (  905): releaseWL(42b29cf0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
I/CheckinService( 2251): Preparing to send checkin request
I/EventLogService( 2251): Accumulating logs since 1450109315069
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 2251): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2251): Using GMS GoogleHttpClient
,D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): releaseWL(43783a08): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,I/SensorManager(  905): mEventCount = 1350
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2251/10028)
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (2251/10028)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/PMS     (  905): Going to sleep due to screen timeout...
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42716668
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42716668, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4288bfb0
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@422a5638
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,W/PMS     (  905): mWirelessDisplayManager is null
D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2251): awaiting user notification for token
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{42505c90 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 6 2 12
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 377ms
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
,D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43bc80c8)
,I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  905): acquireWL(42a96b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/BatteryService(  905): n_update end
I/InputMethodManagerService(  905): Disable input method client, pid=4400
W/ResourceType( 4400): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4400): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{42098318 VFEDH.C. .F...... 0,0-720,1134 #64}
,D/NfcService( 1254): applyRouting -2
D/PMS     (  905): acquireWL(42a3ffc8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null,
D/PMN     (  905): wakingUp
D/PMS     (  905): releaseWL(42a3ffc8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
I/WindowManager(  905): No lock screen! windowToken=null
D/PMS     (  905): releaseWL(42a96b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  905): onScreenOn
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/NfcService( 1254): applyRouting - 0
,D/MtpService( 2475): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2475): [MTP][onReceive]-
,D/NfcService( 1254): applyRouting -2
,D/AutoSetting( 1388): receiver - intent: android.intent.action.USER_PRESENT
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): acquireWL(42af6ea8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMS     (  905): releaseWL(42af6ea8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4612 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/AutoSetting( 1388): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/ClockThread( 1116): stop update clock
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  905): startDataStallAlarm: tag=20443 delay=15s
I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
D/TetherSettings( 4141): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4141): Cust_ConnectToPC   : Internet_Sharing>true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/        ( 4141): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4141): Cust_ConnectToPC   : spcsc>false
D/        ( 4141): Cust_ConnectToPC   : IPT>true
D/        ( 4141): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4141): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4141): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4141): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4141): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/PSReceiver( 4141): onReceive:android.intent.action.USER_PRESENT
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [3][0][0]
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): SET_SCREEN_ON:On
I/wpa_supplicant( 1177): htc_wext_set_keepalive +
I/wpa_supplicant( 1177): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1177): getPrivFuncNum +	
I/wpa_supplicant( 1177): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  905): BroadcastRSSIForIMS, newrssi =-48 , oldRssi= -200
,I/SmartNS_PSService( 4141): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 4141): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4141):  defaultType:0
W/ContextImpl( 4141): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/MultiDex( 4612): install
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,I/MultiDex( 4612): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,D/WifiNative-wlan0(  905):    returned true
,I/MultiDex( 4612): loading existing secondary dex files
,I/MultiDex( 4612): load found 1 secondary dex files
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/MultiDex( 4612): install done
V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,D/NetworkPolicy(  905): updateScreenOn: false
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,I/ProviderInstaller( 4612): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4630 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1837): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1837): onScreenOn: 1450109372347
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1837): onScreenOn: 1450109372347
D/PMS     (  905): acquireWL(4245d340): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1424 10028 null
D/PMS     (  905): releaseWL(4245d340): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/ContextImpl( 4630): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4288bfb0
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4288bfb0, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@422a5638
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  905): goingToSleep
D/PMS     (  905): acquireWL(437fe978): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,D/PMS     (  905): acquireWL(429cca88): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4630 1000 null
,D/SmartSyncUtils( 4630): isEpsOn(), nState = 0
D/PMS     (  905): releaseWL(437fe978): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  905): ACTION_SCREEN_OFF
,I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20443 mDataStallAlarmIntent=PendingIntent{426599b8: PendingIntentRecord{42b20308 android broadcastIntent}}
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): SET_SCREEN_ON:Off
I/wpa_supplicant( 1177): htc_wext_set_keepalive +
I/wpa_supplicant( 1177): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1177): getPrivFuncNum +	
I/wpa_supplicant( 1177): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1177): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1177): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1177): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(427746e8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
,D/PMS     (  905): releaseWL(429cca88): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/PMS     (  905): releaseWL(4366abc8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  905): NetTransition Wakelock for ConnectedState released by timeout
D/NetworkPolicy(  905): updateScreenOn: false
,D/SmartSyncUtils( 4630): getMobilePolicyEnabled, result = true
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  905): killProcessQuiet, pid=4258
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  905):    returned true
D/GCM     ( 1365): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Killing 4258:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PMS     (  905): releaseWL(427746e8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  905): Recipient 4258
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1424/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1868/10178)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1268/10075)
,I/ConnectivityHelper( 1268): [onReceive] WIFI(1): CONNECTED
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,I/NetworkMonitor( 3865): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3865/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4499/10078)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/PMS     (  905): acquireWL(42b8b288): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(42b8b288): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
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
,D/CaptivePortalTracker(  905): NoActiveNetworkState
,I/jxcore-log( 4400): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4400): 
V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): Found interface wlan0
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1895/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4288/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(446f17d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3887/10051)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ContactMessageStore( 1242): start background delete task...
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1424/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4288/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/ContactMessageStore( 1242): size: 0 , 0
D/ContactMessageStore( 1242): Background delete complete
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43ec45e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 905 1000 WorkSource{10106}
,W/ContextImpl( 4630): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4653 uid=10106 gids={50106, 3003, 5012}
,D/PMS     (  905): releaseWL(446f17d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/SmartSyncUtils( 4630): isEpsOn(), nState = 0
E/ExternalAccountType( 1329): Unsupported attribute readOnly
,D/SmartSyncUtils( 4630): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4630): isEpsOn(), nState = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43084488): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/WifiService(  905): New client listening to asynchronous messages
,D/PMS     (  905): releaseWL(43084488): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@422a5638
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@422a5638, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@422a5638, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@422a5638
,D/DotMatrix( 1583): [EventService] getTotalRam: 1873 Mb
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2475/10021)
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4287ec40 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4287ec40 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/PMS     (  905): acquireWL(43ecc048): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1424 10028 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1837): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1837): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1837): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1837): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1837): onScreenOff
D/PMS     (  905): releaseWL(43ecc048): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  905): acquireWL(42c16e28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2251 10028 null
,D/AutoSetting( 1388): service - mHandler: cancel location update
,D/AutoSetting( 1388): service -           changes count: 0
D/PMS     (  905): releaseWL(42c16e28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1365): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10028)
D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1365): [NET] getaddrinfo-,err=8
D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1365): [NET] getaddrinfo-, 1
,D/libc    ( 1365): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =498a +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
D/PMS     (  905): acquireWL(43bb9068): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1365 10028 null
,D/AutoSetting( 1388): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4499): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4499): onReceive CONNECTIVITY_CHANGE networkType=1
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/AutoSetting( 1388): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1388): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1388/10053)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4532/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1388/10053)
D/AutoSetting( 1388): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1388): service - onStartCommand() check timezone in 30000
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 237
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1365): [NET] getaddrinfo_proxy-, success
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [3][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4121/10160)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4121/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1868/10178)
,I/dalvikvm-heap( 4121): Grow heap (frag case) to 13.524MB for 1821008-byte allocation
,D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1365): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10028)
D/PMS     (  905): acquireWL(43c4ff10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
D/PMS     (  905): releaseWL(43c4ff10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/NewsWeather( 4653): LocationClient connecting
,I/NewsWeather( 4653): NewsAccounts: 2, AllSystemAccounts 1.
,E/dalvikvm( 4653): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4653): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4653): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4653): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4653): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,D/GCM     ( 1365): Connected
D/PMS     (  905): acquireWL(43bfab60): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10028)
D/PMS     (  905): releaseWL(43bb9068): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10028)
D/PMS     (  905): releaseWL(43bfab60): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): acquireWL(4466d2f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10028)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1365): Message class mpf
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10028)
,D/PMS     (  905): releaseWL(4466d2f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,I/ProviderInstaller( 4653): Installed default security provider GmsCore_OpenSSL
D/PMS     (  905): acquireWL(43c9a3c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
D/PMS     (  905): releaseWL(43c9a3c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(431af718): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,I/NewsWeather( 4653): Last usage 0, idle 1450109372s, sync interval 2592000s
,I/NewsWeather( 4653): setPeriodicSync in seconds 2592000
D/PMS     (  905): releaseWL(431af718): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4653): onConnected null
,W/GCoreFlp( 1424): No location to return for getLastLocation()
,I/NewsWeather( 4653): LocationClient onConnected: location null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/PMS     (  905): acquireWL(4369ae50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1424 10028 null
D/PMS     (  905): acquireWL(43ccd5b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1424 10028 null
D/PMS     (  905): releaseWL(4369ae50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/PMS     (  905): releaseWL(43ccd5b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4653): Skip sync for lookup editions
,I/NewsWeather( 4653): syncNewsAppData traffic type BACKGROUND_POLL
,W/fb4a(:<default>):UserScope( 4470): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/NewsWeather( 4653): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/fb4a(:<default>):UserScope( 4470): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [7][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,E/NewsWeather( 4653): Unrecoverable authentication exception
E/NewsWeather( 4653): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4653): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4653): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4653): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{421cec78 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 4653): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4653): [NET] getaddrinfo-,err=8
D/libc    ( 4653): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4653): [NET] getaddrinfo-, 1
D/libc    ( 4653): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =7f47 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 10 4 12
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=70
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4653): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4653): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4653): [NET] getaddrinfo-,err=8
,E/fb4a(:<default>):LocalFbBroadcastManager( 4470): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,I/Adreno-EGL( 4612): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4612): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4612): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4612): Local Branch: 
I/Adreno-EGL( 4612): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4612): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4612):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4470/10026)
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=14 [7][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(43dc2618): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,E/NewsWeather( 4653): Failed to syncNewsAppData
,E/NewsWeather( 4653): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  905): releaseWL(43dc2618): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(445dd4a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 68119, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/Process (  905): killProcessQuiet, pid=4288
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  905): releaseWL(43ec45e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
I/ActivityManager(  905): Killing 4288:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/PMS     (  905): releaseWL(445dd4a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1424/10028)
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  905): Recipient 4288
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1329): Unsupported attribute readOnly
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4481bfa8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4481bfa8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4612/10028)
,I/Adreno-EGL( 4612): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4612): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4612): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4612): Local Branch: 
I/Adreno-EGL( 4612): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4612): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4612):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4612): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4612): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4612): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4612): Local Branch: 
I/Adreno-EGL( 4612): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4612): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4612):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4612): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/PMS     (  905): releaseWL(43c7f978): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/CheckinTask( 2251): Sending checkin request (8887 bytes)
D/libc    ( 2251): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2251): [NET] getaddrinfo-,err=8
D/libc    ( 2251): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2251): [NET] getaddrinfo-, 1
,D/libc    ( 2251): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =7c9d +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 268
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2251): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2251): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2251): [NET] getaddrinfo-,err=8
,D/PMS     (  905): acquireWL(43cc5ab0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/PMS     (  905): releaseWL(43cc5ab0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (2251/10028)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (2251/10028)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=4 [22][1][0]
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =e4f6 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2251): awaiting user notification for token
,D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{4242faf8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 10 4 12
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/23.59.123.86
,I/CheckinTask( 2251): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2251): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,D/PMS     (  905): releaseWL(4308b328): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread( 2251): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@421d6990 that was originally bound here
E/ActivityThread( 2251): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@421d6990 that was originally bound here
E/ActivityThread( 2251): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2251): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2251): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2251): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2251): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2251): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2251): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2251): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2251): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2251): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2251): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2251): 	at bks.a(SourceFile:298)
E/ActivityThread( 2251): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2251): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2251): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2251): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1365): GCM config loaded
,D/AutoSetting( 1515): service - handleMessage() stop self
,D/AutoSetting( 1515): service - onDestroy() END
,D/Process (  905): killProcessQuiet, pid=4304
,I/ActivityManager(  905): Killing 4304:com.htc.backup/1000 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/AutoSetting( 1515): service - handleMessage() quit looper
,I/ActivityManager(  905): Recipient 4304
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV2    ( 4532): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 4653): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  905): killProcessQuiet, pid=4328
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4328:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4328
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{43ba0250 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(42395750): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/PMS     (  905): acquireWL(425f9d30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{4229e4e0: PendingIntentRecord{42a267e8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=129648, Int=0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): releaseWL(425f9d30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4292df60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42395750): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(4292df60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(4365a278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4365a278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43b90050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42886ae0: PendingIntentRecord{42918820 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=139020, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43b90050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1388): service - mHandler: update timezone
,D/AutoSetting( 1388): service - handleMessage() stop self
,D/AutoSetting( 1515): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1515): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1515): service - onCreate()
,D/AutoSetting( 1388): service - handleMessage() quit looper
,D/AutoSetting( 1388): service - onDestroy() END
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1515): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1515): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1583): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1515): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1515): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1515): service - mHandler: update timezone
,D/AutoSetting( 1515): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1515): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1515): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1515): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{4247c5a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 2 7 2 11
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  905): killProcessQuiet, pid=3887
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3887:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3887
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{43d6ac20 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  905): acquireWL(42a701a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10028}
,V/AlarmManager(  905): sending alarm PendingIntent{42155278: PendingIntentRecord{42aef528 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141582, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{4229e4e0: PendingIntentRecord{42a267e8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=159666, Int=0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1365/10028)
,D/PMS     (  905): acquireWL(42ab45d0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/PMS     (  905): acquireWL(42a8e618): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
D/PMS     (  905): releaseWL(42a701a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): releaseWL(42a8e618): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): acquireWL(42ab0120): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=3 [29][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(429570f8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 905 1000 WorkSource{10106}
,D/PMS     (  905): releaseWL(42ab45d0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(42ab0120): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(445f7f00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(445f7f00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4653): Last usage 0, idle 1450109420s, sync interval 2592000s
I/NewsWeather( 4653): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4653): Skip sync for lookup editions
,I/NewsWeather( 4653): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4653): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{421cb5f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/NewsWeather( 4653): Unrecoverable authentication exception
E/NewsWeather( 4653): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4653): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4653): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4653): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews.Performance( 1116): com.google.android.gms 2 9 3 12
,D/PMS     (  905): acquireWL(43c58368): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,E/NewsWeather( 4653): Failed to syncNewsAppData
,E/NewsWeather( 4653): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  905): releaseWL(43c58368): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4365d5f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 112412, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  905): releaseWL(429570f8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1424/10028)
D/PMS     (  905): releaseWL(4365d5f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(428f6470): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(428f6470): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1329): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(43c0fa40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43c0fa40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
,D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1515): service - handleMessage() stop self
,D/AutoSetting( 1515): service - onDestroy() END
,D/AutoSetting( 1515): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4346
,I/ActivityManager(  905): Killing 4346:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 4346
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1242): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(43cc1fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4229e4e0: PendingIntentRecord{42a267e8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=189725, Int=0
,D/PMS     (  905): acquireWL(42912af0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): releaseWL(43cc1fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43860ab0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42912af0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(43860ab0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(42b383e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(42b383e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42ab2e98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42886ae0: PendingIntentRecord{42918820 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=199020, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42ab2e98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(44680458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/PMS     (  905): acquireWL(42a42678): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,V/AlarmManager(  905): sending alarm PendingIntent{4229e4e0: PendingIntentRecord{42a267e8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=223598, Int=0
,D/PMS     (  905): releaseWL(44680458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43972d78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=15 [20][3][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(42934cd0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 905 1000 WorkSource{10106}
,D/PMS     (  905): releaseWL(42a42678): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(43972d78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(44662a08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,I/NewsWeather( 4653): Last usage 0, idle 1450109484s, sync interval 2592000s
,I/NewsWeather( 4653): setPeriodicSync in seconds 2592000
D/PMS     (  905): releaseWL(44662a08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4653): Skip sync for lookup editions
,I/NewsWeather( 4653): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4653): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,E/NewsWeather( 4653): Unrecoverable authentication exception
E/NewsWeather( 4653): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4653): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4653): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4653): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4653): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{4223fac0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 2 20 4 12
,D/PMS     (  905): acquireWL(446c0f58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,E/NewsWeather( 4653): Failed to syncNewsAppData
,E/NewsWeather( 4653): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  905): releaseWL(446c0f58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(436f1838): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 160157, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  905): releaseWL(42934cd0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/PMS     (  905): releaseWL(436f1838): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1424/10028)
D/PMS     (  905): acquireWL(437fea68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(437fea68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1329): Unsupported attribute readOnly
,D/PMS     (  905): acquireWL(43bbf248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{425b0050: PendingIntentRecord{42909858 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229702, Int=0
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4714 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{4298e608: PendingIntentRecord{429b3ed0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450109481591, Int=10800000
,D/PMS     (  905): releaseWL(43bbf248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4714/10047)
,D/Process (  905): killProcessQuiet, pid=4275
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4275:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4275
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(4472c620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4472c620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  905): acquireWL(43d2cb40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{4459d7d8: PendingIntentRecord{441c36f0 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=231186, Int=120000
,V/AlarmManager(  905): sending alarm PendingIntent{441eb5f0: PendingIntentRecord{42909858 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231399, Int=0
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,D/PMS     (  905): releaseWL(43d2cb40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2251/10028)
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(440429d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(440429d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43e6a080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{4229e4e0: PendingIntentRecord{42a267e8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=253662, Int=0
,D/PMS     (  905): acquireWL(44072e50): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(428fec30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43e6a080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): releaseWL(44072e50): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(428fec30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(4461fa40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42886ae0: PendingIntentRecord{42918820 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=259020, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4461fa40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(4319c2e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(4319c2e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(440c7300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(440c7300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(44652bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42886ae0: PendingIntentRecord{42918820 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=319020, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(44652bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}

```
