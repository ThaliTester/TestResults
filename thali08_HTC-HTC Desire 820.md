#### Test 56151093b6ab50f_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1111): WifiActivity: 1
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  901):    returned true
,D/PMS     (  901): acquireWL(41d28628): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
D/PMS     (  901): releaseWL(41d28628): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  901): acquireWL(41b0c418): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
D/PMS     (  901): releaseWL(41b0c418): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  901): acquireWL(42e4c238): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
D/PMS     (  901): releaseWL(42e4c238): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  901): acquireWL(4256a188): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
D/PMS     (  901): releaseWL(4256a188): PARTIAL_WAKE_LOCK  Icing 0x1 null
E/cutils-trace( 4525): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4525): ====startRecUseTime====
D/htc.customization.log.level( 4525):  is 
W/CustomizationLogLevel( 4525): Level value is invalid, use default level 2
D/CustomizationManager( 4525):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4525): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4525): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4525): Parsing tag category name = system
I/CustomizationCIDLoader( 4525): Parsing tag category name = application
I/CustomizationCIDLoader( 4525): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4525): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4525): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4525): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4525): Parsing tag category name = Settings
D/CustomizationManager( 4525):  Read CID file spent 0.089 (s)
D/CustomizationManager( 4525):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 4525): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4525): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4525): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4525): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  901): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  901): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  901): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  901): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  901): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  901): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  901): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4525
D/PMS     (  901): acquireHCC(4240ef88): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 901 1000 null
D/PMS     (  901): acquireHCC(42345a80): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 901 1000 null
W/asset   (  901): Copying FileAsset 0x6772c9e8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  901): @test_code: getHtcIntentFlag: 0 obj: 1122983128
D/PMS     (  901): acquireWL(42ef7c28): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 901 1000 null
I/FeedHostManager( 1262): [onPause]
I/FeedProviderManager( 1262): onPause
I/FeedHostManager( 1262): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41ce5a80
I/SocialFeedProvider( 1262): +onPause
I/SocialFeedProvider( 1262): -onPause
I/ActivityManager(  901): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4540 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1262): [trimMemory] 20
W/asset   ( 4540): Copying FileAsset 0x5d7e4c88 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4540): Binding Chromium to main looper Looper (main, tid 1) {41ae74d0}
I/LibraryLoader( 4540): Expected native library version number "",actual native library version number ""
I/chromium( 4540): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4540): Initializing chromium process, renderers=0
D/BluetoothManagerService(  901): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  901): java.lang.Throwable: stack dump
D/BluetoothManagerService(  901): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42064c80:true
W/System.err(  901): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  901): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  901): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  901): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  901): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4540): 1102040840: getState(). Returning 12
D/PMS     (  901): acquireWL(43cdf6f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  901): acquireWL(4307a8a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  901): releaseWL(4307a8a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4540): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4540): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4540): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4540): Local Branch: 
I/Adreno-EGL( 4540): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4540): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4540):                  aa63bbd948f41d15fc72f585e
W/chromium( 4540): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4540): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4540): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4540): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4540): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4540): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4540): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4540): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4540): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4540): CordovaWebView is running on device made by: HTC
,W/AwContents( 4540): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  901): Disable input method client, pid=1262
,W/ResourceType( 4540): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4540): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b2e5b8, mServedView=org.apache.cordova.engine.SystemWebView{41af4220 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  901): Enable input method client, pid=4540
W/XT9_C   ( 1203): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1203): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1203): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1203): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4540): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  901): Displayed com.test.thalitest/.MainActivity: +276ms
,D/PMS     (  901): releaseWL(42ef7c28): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4540): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4540): JniHelper::setJavaVM(0x415bb048), pthread_self() = 1662975808
,D/JX-Cordova( 4540): jxcore cordova android initializing
,D/WIFI_ICON( 1111): WifiActivity: 0
,D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/PluginManager( 4540): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 25ms. Plugin should use CordovaInterface.getThreadPool().
,I/dalvikvm-heap( 4540): Grow heap (frag case) to 11.982MB for 42652-byte allocation
,I/dalvikvm-heap( 4540): Grow heap (frag case) to 12.070MB for 95956-byte allocation
,I/dalvikvm-heap( 4540): Grow heap (frag case) to 12.150MB for 143930-byte allocation
,I/dalvikvm-heap( 4540): Grow heap (frag case) to 12.264MB for 215890-byte allocation
,I/dalvikvm-heap( 4540): Grow heap (frag case) to 12.440MB for 323830-byte allocation
,I/dalvikvm-heap( 4540): Grow heap (frag case) to 12.711MB for 485740-byte allocation
,I/dalvikvm-heap( 4540): Grow heap (frag case) to 13.679MB for 1092904-byte allocation
,I/dalvikvm-heap( 4540): Grow heap (frag case) to 14.631MB for 1639352-byte allocation
,I/SensorManager(  901): mEventCount = 1201
,I/dalvikvm-heap( 4540): Grow heap (frag case) to 15.876MB for 2459024-byte allocation
,I/dalvikvm-heap( 4540): Grow heap (frag case) to 18.061MB for 3688532-byte allocation
,W/CpuWake (  901): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  901): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  901): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  901): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  901): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  901): <<release mCpuPerf_Freq wakelock
D/PMS     (  901): releaseHCC(4240ef88): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  901): releaseHCC(42345a80): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4540): Initializing JXcore engine
,W/jxcore-log( 4540): JXcore engine is ready
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,W/jxcore-log( 4540): Starting JXcore engine
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  901):    returned true
,W/jxcore-log( 4540): Platform android
W/jxcore-log( 4540): 
,W/jxcore-log( 4540): Process ARCH arm
W/jxcore-log( 4540): 
,I/ActivityManager(  901): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4583 uid=10077 gids={50077}
D/PMS     (  901): acquireWL(436be628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10077}
V/AlarmManager(  901): sending alarm PendingIntent{4243d720: PendingIntentRecord{42437978 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453102522507, Int=60000
,D/PMS     (  901): releaseWL(436be628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4583): SMSBackupAgentService started
,D/SMSBackup( 4583): Checking restore status
D/SMSBackup( 4583): Restore complete
,D/SMSBackup( 4583): cancelCheckAlarm
,D/SMSBackup( 4583): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  901): killProcessQuiet, pid=3210
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  901): Killing 3210:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  901): Recipient 3210
,D/WifiDataStallTracker(  901): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  901): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  901): acquireWL(420a2058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
V/AlarmManager(  901): sending alarm PendingIntent{423935e8: PendingIntentRecord{424d8288 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105077, Int=0
D/WifiDataStallTracker(  901): updateDataStallInfo: mDataStallTxRxSum={txSum=136 rxSum=128} preTxRxSum={txSum=135 rxSum=127}
D/WifiDataStallTracker(  901): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  901): onDataStallAlarm: tag=20265 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  901): startDataStallAlarm: tag=20266 delay=15s
D/PMS     (  901): releaseWL(420a2058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4540): JXcore Cordova bridge is ready!
I/jxcore-log( 4540): 
,W/jxcore-log( 4540): JXcore engine is started
,I/chromium( 4540): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  901): releaseWL(43cdf6f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4540): Toggling radios to true
I/jxcore-log( 4540): 
,D/BluetoothAdapter( 4540): enable(): BT is already enabled..!
,D/WifiManager( 4540): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
W/HtcDLNAServiceManager(  901): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  901): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  901): Settings:Agentvalue: 2
W/Settings:Agent(  901): >> traceCallingStack()
W/Settings:Agent(  901): Process.myPid(): 901
W/Settings:Agent(  901): Process.myTid(): 1322
W/Settings:Agent(  901): Process.myUid(): 1000
W/Settings:Agent(  901): 
W/Settings:Agent(  901): 
,W/System.err(  901): java.lang.Throwable: stack dump
W/System.err(  901): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  901): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  901): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  901): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  901): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  901): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  901): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  901): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  901): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  901): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  901): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  901): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  901): 
W/Settings:Agent(  901): << traceCallingStack(): 1(ms)
,D/WifiManager( 4540): disconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiManager( 4540): reconnect: Base Package Name=com.test.thalitest, uid=10189
,D/WifiNative-wlan0(  901): doBoolean: DISCONNECT
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): TDLS: Tear down peers
I/wpa_supplicant( 1171): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4540): Radios toggled
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4540): 
D/WifiService(  901): New client listening to asynchronous messages
D/WifiService(  901): setWifiEnabled: true pid=4540, uid=10189
E/WifiService(  901): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  901): isSprintWifiRestricted(): false
I/WifiService(  901): isMdmWifiRestricted(): false
D/WifiSettingsStore(  901): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1171): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1171): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
,D/HTCRequest(  901): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  901): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  901): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  901): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  901): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  901): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  901): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  901): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  901): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  901): WifiMonitor:getFreqFromEventString() 2412
D/Tethering(  901): interfaceLinkStateChanged wlan0, false
D/Tethering(  901): interfaceStatusChanged wlan0, false,
D/WifiMonitor(  901): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/Tethering(  901): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1171): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1171): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1171): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1171): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1171): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8b2bbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1171):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1171): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1171): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1171): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1171): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1171): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1171): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1171): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1171): EAPOL: External notification - portEnabled=0
,D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1171): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1171): nl80211: if_removed already cleared - ignore event,
D/wpa_supplicant( 1171): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1171): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1171): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1171): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1171): nl80211: Event message available
D/wpa_supplicant( 1171): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1171): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  901):    returned true
D/WifiPerfLock(  901): release()
D/WifiStateMachine(  901): PerfLock released for exiting ConnectedState
D/Tethering(  901): interfaceLinkStateChanged wlan0, false
,D/Tethering(  901): interfaceStatusChanged wlan0, false
D/Tethering(  901): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  901): doBoolean: DRIVER POWERMODE 0
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  901): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  901): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/ConnectivityService(  901): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  901): acquireWL(4265ff50): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 901 1000 null
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): Power_Mode_Type mode = 0
I/wpa_supplicant( 1171): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  901):    returned true
D/libc    (  901): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  901): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  901): [RunningState] Stop DHCP
D/WifiP2pService(  901): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  901): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  901): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  901): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/WifiNative-wlan0(  901): doBoolean: RECONNECT
D/libc    (  901): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): Fast associate: Old scan results
I/wpa_supplicant( 1171): wpa_supplicant_scan enter
I/wpa_supplicant( 1171): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1171): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1171): wpa_supplicant_trigger_scan +
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1171): Scan req (ret=0) - timeout 30 secs
D/HTCRequest(  901): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1171): nl80211: Event message available
D/wpa_supplicant( 1171): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  901): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  901):    returned true
D/WifiStateMachine(  901): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  901): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  901): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  901): stopDataStallAlarm: current tag=20266 mDataStallAlarmIntent=PendingIntent{4262cd58: PendingIntentRecord{424d8288 android broadcastIntent}}
,D/WifiNative-wlan0(  901): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): Power_Mode_Type mode = 0
I/wpa_supplicant( 1171): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 61
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  901):    returned true
D/UsbnetStateTracker(  901): isAvailable+-
D/UsbnetStateTracker(  901): reconnect
,D/UsbnetStateTracker(  901): isAvailable+-
D/WifiStateTracker(  901): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  901): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/WifiP2pService(  901): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  901): Provision feature enable=false
D/ConnectivityService(  901): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1841/10178)
D/ConnectivityService(  901): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/ConnectivityService(  901): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  901): default: reconnect()
D/MDST    (  901): default: setTeardownRequested(false)
D/MDST    (  901): default: setEnableApn apnType =default , enable=true
,D/ConnectivityService(  901): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  901): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  901): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  901): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiDataStallTracker(  901): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 4279): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  901): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  901): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  901): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  901): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  901): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
,D/ConnectivityService(  901): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  901): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  901): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  901): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  901): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  901): handleConnectivityChange: resetting
D/ConnectivityService(  901): resetConnections(wlan0, 3)
D/WifiService(  901): New client listening to asynchronous messages
,D/WISPrService( 4279): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] entry_id:7   entry:0xb78fb1f0  removed 
D/libc    (  364): [NET] entry_id:9   entry:0xb78faf78  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb78fb8f8  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb78fad90  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb78fb7d0  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb78fb310  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb78fb428  removed 
D/libc    (  364): [NET] entry_id:10   entry:0xb78fae58  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb78fb0e8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb78fb4f0  removed 
D/libc    (  364): [NET] entry_id:11   entry:0xb78fb030  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/WISPrService( 4279): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  901): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4279): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  901): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1841/10178)
D/ConnectivityService(  901): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  901): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  901): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/QuickSettingWifi( 1111): receive.wifiConnect:false wifiAPname:null elapse:1
D/WirelessDisplayService(  901): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  901): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  901): startScan Pid: 901 Uid 1000
D/ConnectivityService(  901): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  901): acquireWL(424bdd78): PARTIAL_WAKE_LOCK  NetworkStats 0x1 901 1000 null
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/ConnectivityService(  901): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  901): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  901): getNetworkInfo networkType=1 called by  (901/1000)
,D/WifiNative-wlan0(  901): doBoolean: SCAN
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  901):    returned false
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/BatSI   (  901): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  901): releaseWL(424bdd78): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/QuickSettingWifi( 1111): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  901): acquireWL(4247c738): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
D/ConnectivityService(  901): mActiveDefaultNetwork: -1
D/PMS     (  901): acquireWL(4411ed68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  901): releaseWL(4411ed68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  901): reportInetCondition for net -1, percentage: 0 by  (1364/10028)
D/ConnectivityService(  901): handleInetConditionChange: no active default network - ignore
D/PMS     (  901): releaseWL(4247c738): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
,V/Tethering(  901): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  901): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  901): bSetPropertyMultiRAB:false
D/Tethering(  901): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,D/CaptivePortalTracker(  901): DelayedCaptiveCheckState
D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  901): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  901): getNetworkInfo networkType=1 called by  (901/1000)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/PMS     (  901): acquireWL(4253d1a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 901 1000 null
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/ConnectivityService(  901): getNetworkInfo networkType=1 called by com.google.android.music (3915/10154)
D/GpsLocationProvider(  901): [handleMessage] UPDATE_NETWORK_STATE
D/CaptivePortalTracker(  901): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  901): NoActiveNetworkState
I/Tethering(  901): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,D/GpsLocationProvider(  901): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/Tethering(  901): ipv4Default null
I/Tethering(  901): No IPv4 upstream interface, giving up.
,D/Tethering(  901): TetherMasterSM: InitialState processMessage what=3
I/NetworkMonitor( 3915): type=WIFI subType= reason=null isConnected=false
D/GpsLocationProvider(  901): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  901): ignore wifi update if we are not in OPENING or CLOSING
D/htcCheckinService(  901): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  901): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1262): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  901): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1841/10178)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1439/10028)
D/PMS     (  901): releaseWL(4253d1a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.apps.docs (4424/10100)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1899/1000)
D/ConnectivityService(  901): getNetworkInfo networkType=1 called by com.htc.launcher (1262/10075)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.apps.docs (4424/10100)
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (1990/10021)
,I/ActivityManager(  901): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4605 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4605): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4605): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4605): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4605): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4605): Preparing secondary program dexes.
,V/DexLibLoader( 4605): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4605): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4605): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4605): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4605): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4605): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4605): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4605): Dex already copied
D/OdexVerifier( 4605): Odex verification is skipped.
,V/DexLibLoader( 4605): Creating class loader
,V/DexLibLoader( 4605): Finished creating class loader
V/DexLibLoader( 4605): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4605): Dex already copied
D/OdexVerifier( 4605): Odex verification is skipped.
,V/DexLibLoader( 4605): Creating class loader,
V/DexLibLoader( 4605): Finished creating class loader
V/DexLibLoader( 4605): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar,
V/DexLibLoader( 4605): Dex already copied
D/OdexVerifier( 4605): Odex verification is skipped.
,V/DexLibLoader( 4605): Creating class loader
,V/DexLibLoader( 4605): Finished creating class loader
V/DexLibLoader( 4605): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4605): Dex already copied
D/OdexVerifier( 4605): Odex verification is skipped.
,V/DexLibLoader( 4605): Creating class loader,
V/DexLibLoader( 4605): Finished creating class loader
,V/DexLibLoader( 4605): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4605): DexLibLoader.ensureDexLoaded took 19 ms
,W/dalvikvm( 4605): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4605): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4605): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4605): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4605): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4605): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4605): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4605): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1171): nl80211: Event message available
D/wpa_supplicant( 1171): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1171): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1171): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1171): nl80211: Survey data missing
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1171): Sorted scan results
I/wpa_supplicant( 1171): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1171): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1171): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1171): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1171): [NULL] fc:94:e3:11:35:3a freq=2462 level=-90
D/wpa_supplicant( 1171): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1171): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1171): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1171): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1171): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1171): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1171): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1171): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1171): wpa_supplicant_pick_network+
I/wpa_supplicant( 1171): Selecting BSS from priority group 1
I/wpa_supplicant( 1171): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1171): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1171): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1171): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1171): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1171):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1171):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 1171): Start print parameters
I/wpa_supplicant( 1171): wpa_s->wpa_state is 3
I/wpa_supplicant( 1171): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1171): isConcurrentMode() is 0
I/wpa_supplicant( 1171): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1171): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1171): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1171): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1171): wpa_s->reassociate is 1
I/wpa_supplicant( 1171): wpa_s->is_screen_on 1
I/wpa_supplicant( 1171): wpa_s->ifname wlan0
I/wpa_supplicant( 1171): End print parameters
I/wpa_supplicant( 1171): selected network = 2
D/wpa_supplicant( 1171): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8b2d4e8  current_ssid=0x0
D/wpa_supplicant( 1171): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1171): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1171): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1171): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1171): check if in concurrent case
I/wpa_supplicant( 1171): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' fre,q=2412 MHz)
,W/dalvikvm( 4605): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/wpa_supplicant( 1171): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1171): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1171): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1171): RSN: PMKSA cache search - network_ctx=0xb8b2d4e8 try_opportunistic=0
D/wpa_supplicant( 1171): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1171): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1171): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1171): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1171): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1171): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 6,
D/wpa_supplicant( 1171): nl80211: Unsubscribe mgmt frames handle 0xb8b2c718 (mode change)
D/wpa_supplicant( 1171): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8b2c718
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb8b2c718
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb8b2c718
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb8b2c718
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb8b2c718
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb8b2c718
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb8b2c718
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb8b2c718
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb8b2c718
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb8b2c718
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Register frame type=0xd0 nl_handle=0xb8b2c718,
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1171): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1171):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1171):   * freq=2412
D/wpa_supplicant( 1171):   * Auth Type 0
D/wpa_supplicant( 1171):   * WPA Versions 0x2
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1171): nl80211: Connect request send successfully
D/wpa_supplicant( 1171): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  901): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  901): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  901): doString: LIST_DONGLES
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  901): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987",
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1171): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1171): reply (631) for get BSS: id=0
I/wpa_supplicant( 1171): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1171): freq=5220
I/wpa_supplicant( 1171): level=-48
I/wpa_supplicant( 1171): tsf=0000000108011157
I/wpa_supplicant( 1171): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1171): ssid=NG7005g
I/wpa_supplicant( 1171): ====
I/wpa_supplicant( 1171): id=1
I/wpa_supplicant( 1171): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1171): freq=2412
I/wpa_supplicant( 1171): level=-50
I/wpa_supplicant( 1171): tsf=0000000108011170
I/wpa_supplicant( 1171): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1171): ssid=01ABC
I/wpa_supplicant( 1171): ====
I/wpa_supplicant( 1171): id=2
I/wpa_supplicant( 1171): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1171): freq=2412
I/wpa_supplicant( 1171): level=-50
I/wpa_supplicant( 1171): tsf=0000000108011173
I/wpa_supplicant( 1171): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1171): ssid=NG700
I/wpa_supplicant( 1171): ====
I/wpa_supplicant( 1171): id=3
I/wpa_supplicant( 1171): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1171): freq=2427
I/wpa_supplicant( 1171): level=-77
I/wpa_supplicant( 1171): tsf=0000000108011177
I/wpa_supplicant( 1171): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1171): ssid=Gonzos
I/wpa_supplicant( 1171): ====
I/wpa_supplicant( 1171): id=4
I/wpa_supplicant( 1171): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1171): freq=2462
I/wpa_supplicant( 1171): level=-90
I/wpa_supplicant( 1171): tsf=0000000108011181
I/wpa_supplicant( 1171): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1171): ssid=UPC0039325
I/wpa_supplicant( 1171): ####
,D/WirelessDisplayService(  901): getDiscoveryDongleList
D/WifiStateMachine(  901): == begin of scan result ==
,D/WifiStateMachine(  901): == (5) end of scan result ==
,D/WirelessDisplayService(  901): getDiscoveryDongleList
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/WifiStateMachine(  901): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 108011157, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 108011170, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 108011173, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 108011177, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 108011181, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  901): add 5 to mScanResults
D/BatSI   (  901): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  901): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,E/FbInjectorInitializer( 4605): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1171): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1171): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1171): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1171): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1171): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1171): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1171): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1171): nl80211: Event message available
D/wpa_supplicant( 1171): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1171): nl80211: Connect event
D/Tethering(  901): interfaceLinkStateChanged wlan0, false
D/Tethering(  901): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1171): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1171): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1171): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1171): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1171): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1171): Add randomness: count=11 entropy=5
I/wpa_supplicant( 1171): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1171): TDLS: Remove peers on association
D/wpa_supplicant( 1171): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  901): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1171): EAPOL: SUPP_PAE entering state CONNECTING
D/WifiMonitor(  901): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/wpa_supplicant( 1171): EAPOL: enable timer tick
D/wpa_supplicant( 1171): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1171): htc_wext_set_keepalive +
I/wpa_supplicant( 1171): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1171): getPrivFuncNum +	
I/wpa_supplicant( 1171): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1171): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1171): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1171): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1171): Get randomness: len=32 entropy=6
D/WifiMonitor(  901): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  901): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  901): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  901): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  901): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  901): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  901): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  901): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  901): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  901): WifiMonitor:g,etSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  901): Enter handleAssociatedWithEvent
D/WifiStateMachine(  901): Associated
D/WifiStateMachine(  901): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  901): Exit handleAssociatedWithEvent
D/Tethering(  901): [isWifi] getHotspotEnabled: false
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  901): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  901): interfaceLinkStateChanged wlan0, true
D/WifiStateMachine(  901): BSSID was changed, update WiFi database
D/Tethering(  901): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  901): updateConnectedAP...
D/Tethering(  901): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  901): updateConnectedAP...
,D/WifiStateMachine(  901): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  901): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  901): This record is existed, only update it...
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  901): updateConnectedAP...
I/wpa_supplicant( 1171): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8b2c9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1171):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1171): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1171): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f91b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1171):    broadcast key
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  901): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1171): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1171): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1171): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1171): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  901): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1171): wlan0: Connect to SSID: NG700
D/WifiMonitor(  901): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1171): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1171): set send_ind_to_ndc = 0
I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING - ret = 0
,D/wpa_supplicant( 1171): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1171): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1171): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1171): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1171): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1171): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: SUPP_BE entering state IDLE
D/HTCRequest(  901): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1171): EAPOL authentication completed successfully
I/wpa_supplicant( 1171): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 79
D/HTCRequest(  901): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1171): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1171): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1171): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  901): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  901): interfaceLinkStateChanged wlan0, true
D/Tethering(  901): interfaceStatusChanged wlan0, true
,D/Tethering(  901): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  901): updateConnectedAP...
,D/WifiStateMachine(  901): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  901): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  901): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  901): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  901): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  901): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  901): This record is existed, only update it...
I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  901): updateConnectedAP...
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  901): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  901): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  901): Provision feature enable=false
,D/ConnectivityService(  901): mActiveDefaultNetwork: -1
D/WISPrService( 4279): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4279): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  901): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  901): updateConnectedAP...
,D/DhcpStateMachine(  901): [StoppedState] Start DHCP
D/WifiStateMachine(  901): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  901):    returned true
,D/WifiNative-wlan0(  901): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): Power_Mode_Type mode = 1
I/wpa_supplicant( 1171): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doString: DRIVER WLS_BATCHING GET
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  901):    returned null
E/WifiStateMachine(  901): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  901): doString: DRIVER WLS_BATCHING STOP
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiStateMachine(  901): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  901): acquireWL(42c7d3a8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 901 1000 null
,D/WifiStateMachine(  901): handlePreDhcpSetup mBluetoothConnectionActive: false
,D/WifiNative-wlan0(  901):    returned null
D/WifiP2pService(  901): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424eb048 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424eb048 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1111): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4605): Verify
,D/WifiService(  901): New client listening to asynchronous messages
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4605): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4605): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4605): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  901): killProcessQuiet, pid=4360
,I/ActivityManager(  901): Killing 4360:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/PMS     (  901): acquireWL(44231cd0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1225 10028 null
,I/ActivityManager(  901): Recipient 4360
,D/PMS     (  901): acquireWL(4260c040): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1225 10028 null
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  901): Client connection lost with reason: 4
,D/PMS     (  901): releaseWL(44231cd0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1225/10028),
,D/PMS     (  901): releaseWL(4260c040): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1364): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1225/10028)
,D/AutoSetting( 1398): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  901): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4634 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.htc.sense.hsp (1398/10053)
,D/AutoSetting( 1398): Util - no network available!
D/ConnectivityService(  901): getActiveNetworkInfo called by com.htc.sense.hsp (1398/10053)
,D/AutoSetting( 1398): service - onCreate()
,D/AutoSetting( 1398): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1398): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  901): request 4236b240 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  901): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 1398): service - mHandler: cancel location update
,D/AutoSetting( 1398): service -           changes count: 0
,D/libc    (  901): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  901): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent DefaultState
,W/fb4a(:<default>):UserScope( 4605): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4605): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4605): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4634): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4634): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4634): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4634): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  901): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4662 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.setupwizard (4634/10078)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.setupwizard (4634/10078)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.setupwizard (4634/10078)
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4605): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/dalvikvm( 4605): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4605): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4605): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4605): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4605): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4605): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4605): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4605): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;,
W/dalvikvm( 4605): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,E/dalvikvm( 4605): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4605): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4605): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4605): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4605): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4605): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4605): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4605): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4605): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/ActivityManager(  901): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4687 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  901): killProcessQuiet, pid=3897
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  901): Killing 3897:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/dalvikvm-heap( 4605): Grow heap (frag case) to 9.913MB for 39954-byte allocation
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4687): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/dalvikvm-heap( 4605): Grow heap (frag case) to 9.989MB for 79892-byte allocation
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4687): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4687): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4687): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4687): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/libc    (  901): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  901): [NET] getaddrinfo-, SUCCESS
D/libc    (  901): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  901): [NET] getaddrinfo-, SUCCESS
D/libc    (  901): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  901): [NET] getaddrinfo-, SUCCESS
D/libc    (  901): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  901): [NET] getaddrinfo-, SUCCESS
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  901): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): Power_Mode_Type mode = 0
I/wpa_supplicant( 1171): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  901):    returned true
,D/WifiNative-wlan0(  901): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,I/dalvikvm-heap( 4605): Grow heap (frag case) to 10.035MB for 84664-byte allocation
,D/WifiNative-wlan0(  901):    returned true
,D/WifiStateMachine(  901): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  901): Recipient 3897
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiP2pService(  901): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  901): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  901): releaseWL(42c7d3a8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
D/WIFI_ICON( 1111): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  901):    returned true
D/WifiStateMachine(  901): gateway: /192.168.1.1
D/WifiNative-wlan0(  901): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  901):    returned true
D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  901): VerifyingLinkState enter
D/WifiStateMachine(  901): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  901): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  901): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  901): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -49, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  901): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  901): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  901): startDataStallAlarm: tag=20268 delay=15s
V/NetworkPolicy(  901): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WISPrService( 4279): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/WifiWatchdogStateMachine(  901): WAN detection
D/libc    (  901): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  901): [NET] getaddrinfo-, SUCCESS
D/WifiStateTracker(  901): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  901): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  901): Provision feature enable=false
D/ConnectivityService(  901): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  901): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  901): default: teardown()
D/MDST    (  901): default: setTeardownRequested(true)
D/MDST    (  901): default: setEnableApn apnType =default , enable=false
D/MDST    (  901): default: setTeardownRequested(true)
D/ConnectivityService(  901): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1111): WifiActivity: 3
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/ConnectivityService(  901): Unexpected mtu value: android.net.wifi.WifiStateTracker@42417610
,D/ConnectivityService(  901): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  901): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/WifiStateMachine(  901): syncGetConfiguredNetworks
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  901): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  901): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  901): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  901): handleConnectivityChange: resetting
D/Nat464Xlat(  901): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  901): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  901): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  901): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  901): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  901): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  901): acquireWL(4358a4e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 901 1000 null
,I/QuickSettingWifi( 1111): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/WirelessDisplayService(  901): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
D/WirelessDisplayService(  901):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.setupwizard (4634/10078)
D/ConnectivityService(  901): getNetworkInfo networkType=1 called by  (901/1000)
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  901): acquireWL(441a5b90): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1225 10028 null
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.apps.magazines (4687/10151)
D/PMS     (  901): acquireWL(4338d130): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1225 10028 null
D/PMS     (  901): releaseWL(441a5b90): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,V/WebViewChromiumFactoryProvider( 4687): Binding Chromium to main looper Looper (main, tid 1) {41adf400}
,I/LibraryLoader( 4687): Expected native library version number "",actual native library version number ""
,I/chromium( 4687): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4687): Initializing chromium process, renderers=0
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1225/10028)
I//system/bin/ip(  364): RTNETLINK answers: No such process
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/CheckinService( 1225): Preparing to send checkin request
,I/EventLogService( 1225): Accumulating logs since 1453102472445
,E/AudioManagerAndroid( 4687): BLUETOOTH permission is missing!
D/PMS     (  901): acquireWL(4387eaa0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  901): acquireWL(43c654c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  901): releaseWL(4387eaa0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  901): mActiveDefaultNetwork: WIFI
I/dalvikvm-heap( 4605): Grow heap (frag case) to 10.280MB for 75760-byte allocation
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,I/Adreno-EGL( 4687): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4687): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4687): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4687): Local Branch: 
I/Adreno-EGL( 4687): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4687): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4687):                  aa63bbd948f41d15fc72f585e
D/PMS     (  901): releaseWL(4358a4e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/GoogleHttpClient( 1225): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1225): Using GMS GoogleHttpClient
D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
W/BroadcastQueue(  901): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43874a08 u0 ReceiverList{4385a290 4605 com.facebook.katana/10026/u0 remote:43855b40}}
W/BroadcastQueue(  901): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43874a08 u0 ReceiverList{4385a290 4605 com.facebook.katana/10026/u0 remote:43855b40}}
W/BroadcastQueue(  901): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43d93970 u0 ReceiverList{43d93910 4605 com.facebook.katana/10026/u0 remote:43d21850}}
,D/ConnectivityService(  901): getNetworkInfo networkType=9 called by com.google.android.gms (1225/10028)
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  901): getNetworkInfo networkType=0 called by com.google.android.gms (1225/10028)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,I/NSApplication( 4687): Starting up...
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.apps.magazines (4687/10151)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.apps.magazines (4687/10151)
,D/wpa_supplicant( 1171): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1171): EAPOL: disable timer tick
,D/PMS     (  901): acquireWL(44493118): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1439 10028 null
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/PMS     (  901): releaseWL(44493118): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/Process (  901): killProcessQuiet, pid=4394
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/jxcore-log( 4540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4540): 
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.apps.plus (4257/10160)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.apps.plus (4257/10160)
I/ActivityManager(  901): Killing 4394:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
D/ConnectivityService(  901): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1841/10178)
I/ActivityManager(  901): Recipient 4394
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GCoreFlp( 1439): Unknown pending intent to remove.
D/ConnectivityService(  901): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1841/10178)
D/PMS     (  901): acquireWL(438621a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1439 10028 null
D/PMS     (  901): releaseWL(438621a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ConnectivityService(  901): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1841/10178)
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1111): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1225): awaiting user notification for token
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41ecc0d0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.google.android.gms 1 7 3 12
,I/ActivityManager(  901): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4744 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4605): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4605): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/MultiDex( 4744): install
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
I/MultiDex( 4744): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4744): loading existing secondary dex files
I/MultiDex( 4744): load found 1 secondary dex files
I/MultiDex( 4744): install done
,I/ProviderInstaller( 4744): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Adreno-EGL( 4744): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4744): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4744): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4744): Local Branch: 
I/Adreno-EGL( 4744): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4744): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4744):                  aa63bbd948f41d15fc72f585e
,I/jxcore-log( 4540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4540): 
,I/Adreno-EGL( 4744): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4744): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4744): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4744): Local Branch: 
I/Adreno-EGL( 4744): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4744): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4744):                  aa63bbd948f41d15fc72f585e
,I/jxcore-log( 4540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4540): 
,D/WIFI_ICON( 1111): WifiActivity: 1
,D/PMS     (  901): releaseWL(4265ff50): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/ConnectivityService(  901): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  901): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  901): [AlarmQueuing] connectivity wifi: true
,D/CaptivePortalTracker(  901): NoActiveNetworkState
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/ConnectivityService(  901): getNetworkInfo networkType=1 called by  (901/1000)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/PMS     (  901): acquireWL(4237e960): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 901 1000 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1899/1000)
D/htcCheckinService(  901): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  901): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
I/acms    ( 1899): Checking Certificates
I/acms    ( 1899): Checking Developer Certificates
I/acms    ( 1899): Checking Application Certificates
I/acms    ( 1899): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto),
I/acms    ( 1899): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1899): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1899): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1899): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1899): Updating next query delay: 75600000
I/mlserverapp( 1899): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1899): cancelACMSProgrammedChecks
,D/CaptivePortalTracker(  901): DelayedCaptiveCheckState
W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,V/Tethering(  901): bSetPropertyMultiRAB:false
D/ConnectivityService(  901): getActiveNetworkInfo called by com.htc.musicenhancer (3938/10051)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.apps.docs (4424/10100)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1439/10028)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1439/10028)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.setupwizard (4634/10078)
D/ConnectivityService(  901): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1841/10178)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/ConnectivityService(  901): getNetworkInfo networkType=1 called by com.google.android.music (3915/10154)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/Tethering(  901): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  901): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  901): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  901): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  901): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  901): Found interface wlan0
,D/Tethering(  901): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 3915): type=WIFI subType= reason=null isConnected=true
,I/ConnectivityHelper( 1262): [onReceive] WIFI(1): CONNECTED
D/PMS     (  901): acquireWL(425146e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.apps.docs (4424/10100)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
D/ConnectivityService(  901): getNetworkInfo networkType=1 called by com.htc.launcher (1262/10075)
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1990/10021)
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  901): acquireWL(43573598): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 901 1000 WorkSource{10106}
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
I/ActivityManager(  901): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4767 uid=10106 gids={50106, 3003, 5012}
D/GpsLocationProvider(  901): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  901): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  901): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  901): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  901): releaseWL(425146e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  901): releaseWL(4237e960): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  901): acquireWL(425ab600): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1225 10028 null
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  901): releaseWL(425ab600): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1364): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1364): [NET] getaddrinfo-,err=8
D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1364): [NET] getaddrinfo-, 1
,D/libc    ( 1364): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =aeb9 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  901): acquireWL(4359d5e8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1364 10028 null
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1225/10028)
,D/AutoSetting( 1398): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4634): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4634): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  901): getActiveNetworkInfo called by com.htc.sense.hsp (1398/10053)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.apps.magazines (4687/10151)
,D/AutoSetting( 1398): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1398): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1398): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1398): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1398): service - handleMessage() setting current location null
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/AutoSetting( 1398): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1398): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.apps.plus (4257/10160)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.htc.sense.hsp (1398/10053)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.apps.plus (4257/10160)
D/ConnectivityService(  901): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1841/10178)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 240
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1364): [NET] getaddrinfo_proxy-, success
,I/dalvikvm-heap( 4257): Grow heap (frag case) to 13.500MB for 1821008-byte allocation
,I/NewsWeather( 4767): LocationClient connecting
,I/NewsWeather( 4767): NewsAccounts: 2, AllSystemAccounts 1.
,D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1364): [NET] getaddrinfo-,err=8
,E/dalvikvm( 4767): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4767): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4767): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4767): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4767): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  901): acquireWL(4235bc18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
D/PMS     (  901): releaseWL(4235bc18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/ProviderInstaller( 4767): Installed default security provider GmsCore_OpenSSL
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(43d938d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,I/NewsWeather( 4767): onConnected null
D/PMS     (  901): releaseWL(43d938d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4767): Last usage 0, idle 1453102527s, sync interval 2592000s
,I/NewsWeather( 4767): setPeriodicSync in seconds 2592000
,W/GCoreFlp( 1439): No location to return for getLastLocation()
D/PMS     (  901): acquireWL(42e03898): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1439 10028 null
D/PMS     (  901): acquireWL(43341f80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1439 10028 null
,D/PMS     (  901): releaseWL(42e03898): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
I/NewsWeather( 4767): LocationClient onConnected: location null
,D/PMS     (  901): releaseWL(43341f80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCM     ( 1364): Connected
I/NewsWeather( 4767): Skip sync for lookup editions
,I/NewsWeather( 4767): syncNewsAppData traffic type BACKGROUND_POLL
D/PMS     (  901): acquireWL(425a94b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  901): releaseWL(4359d5e8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
,I/NewsWeather( 4767): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
D/ConnectivityService(  901): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  901): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  901): handleInetConditionChange: starting a change hold
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  901): releaseWL(425a94b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  901): acquireWL(4265f258): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
,D/ConnectivityService(  901): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
,D/ConnectivityService(  901): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1364): Message class mpf
D/ConnectivityService(  901): handleInetConditionChange: currently in hold - not setting new end evt
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  901): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  901): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  901): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (4744/10028)
D/PMS     (  901): releaseWL(4265f258): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  901): acquireWL(42381928): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,I/Adreno-EGL( 4744): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4744): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4744): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4744): Local Branch: 
I/Adreno-EGL( 4744): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4744): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4744):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  901): releaseWL(42381928): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1111): com.google.android.gms (false,0)
,W/Settings( 4744): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/NewsWeather( 4767): Unrecoverable authentication exception
E/NewsWeather( 4767): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4767): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4767): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4767): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41d8dd38 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.google.android.gms 4 7 2 12
,D/libc    ( 4767): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4767): [NET] getaddrinfo-,err=8
D/libc    ( 4767): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4767): [NET] getaddrinfo-, 1
,D/libc    ( 4767): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =6c33 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,I/CheckinTask( 1225): Sending checkin request (8975 bytes)
D/libc    ( 1225): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1225): [NET] getaddrinfo-, 1
,D/libc    ( 1225): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b5ca +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=70
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4767): [NET] getaddrinfo_proxy-, success
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 172
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1225): [NET] getaddrinfo_proxy-, success
,I/jxcore-log( 4540): Test app app.js loaded
I/jxcore-log( 4540): 
,I/Choreographer( 4540): Skipped 288 frames!  The application may be doing too much work on its main thread.
,D/libc    ( 4767): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4767): [NET] getaddrinfo-,err=8
,I/chromium( 4540): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/libc    ( 1225): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
,D/PMS     (  901): acquireWL(42e2cdb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  901): releaseWL(42e2cdb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4767): Failed to syncNewsAppData
,E/NewsWeather( 4767): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4259a830): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/SyncManager(  901): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 67735, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/Process (  901): killProcessQuiet, pid=4424
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  901): releaseWL(43573598): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,I/ActivityManager(  901): Killing 4424:com.google.android.apps.docs/u0a100 (adj 15): empty #17
W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1439/10028)
D/PMS     (  901): releaseWL(4259a830): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/PMS     (  901): acquireWL(42435528): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,W/dalvikvm( 4540): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/PMS     (  901): releaseWL(42435528): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4540): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4540): BLE advertisement is supported
I/jxcore-log( 4540): 
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
,D/ConnectivityService(  901): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  901): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=5 [35][2][0]
,D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/WIFI_ICON( 1111): WifiActivity: 3
,D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/ActivityManager(  901): Recipient 4424
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PMS     (  901): Going to sleep due to screen timeout...
,I/SensorManager(  901): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421a72e0
W/SensorService(  901): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  901): disable: get sensor name = CM36282 Light sensor
W/SensorService(  901): pid=901, uid=1000
W/SensorService(  901): Active sensors: size = 2
W/SensorService(  901): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  901): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  901): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421a72e0, eanble = 0, strlen(mName) = 59
W/SensorService(  901): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  901): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422deca0
W/SensorService(  901): Listener[1] = com.htc.smartdim.sensor_eye@4262c460
,W/SensorService(  901): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  901): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  901): Couldn't get kernel wake lock stats
V/LightsService(  901): setLight #2: color=#0
D/qdlights(  901): set_light_buttons_func: on=0 brightness=0
V/LightsService(  901): setLight #0: color=#0
,D/WirelessDisplayService(  901): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  901): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  901): mWirelessDisplayManager is null
,D/PMS     (  901): acquireWL(43c54fb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  901): releaseWL(43c54fb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  901): getNetworkInfo networkType=9 called by com.google.android.gms (1225/10028)
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  901): getNetworkInfo networkType=0 called by com.google.android.gms (1225/10028)
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [1][0][0]
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1225): awaiting user notification for token
,I/RemoteViews( 1111): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41ebc288 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.google.android.gms 1 6 3 12
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  901): BroadcastRSSIForIMS, newrssi =-50 , oldRssi= -200
D/WIFI_ICON( 1111): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  901):    returned true
,D/SurfaceControl(  901): Excessive delay in blankDisplay() while turning screen off: 388ms
D/PMS     (  901): nativeSetInteractive:false
D/PMS     (  901): nativeSetInteractive:false done
D/PMS     (  901): nativeSetAutoSuspend:true
D/PMS     (  901): nativeSetAutoSuspend:true done
D/HABCtrl (  901): TPE algorithm. remove timeout.
,D/NfcService( 1249): ScreenObserver: OFF
I/InputManager(  901): Cancel all due to getting PMS screen off broadcast
D/PMS     (  901): OOBE c monitor 11
I/InputMethodManagerService(  901): screenObserver, isScreenOn=false
,D/NfcService( 1249): applyRouting - 0
,D/NfcService( 1249): applyRouting -2
,V/KeyguardServiceDelegate(  901): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42ed4a48)
I/InputMethodManagerService(  901): Disable input method client, pid=4540
D/PMS     (  901): acquireWL(42e96360): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1249 1027 null
D/PMS     (  901): acquireWL(425ed2a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/PMN     (  901): wakingUp
,I/BatteryService(  901): n_update end
I/IntentController( 1111): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
W/ResourceType( 4540): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4540): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41af4220 VFEDH.C. .F...... 0,0-720,1134 #64}
,V/KeyguardServiceDelegate(  901): **** SHOWN CALLED ****
D/WirelessDisplayService(  901): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  901): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  901): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  901): releaseWL(42e96360): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  901): releaseWL(425ed2a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  901): No lock screen! windowToken=null
D/PMN     (  901): onScreenOn
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
D/MtpService( 1990): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1249): applyRouting - 0
D/MtpService( 1990): [MTP][onReceive]-
,D/AutoSetting( 1398): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1249): applyRouting -2
D/WirelessDisplayService(  901): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  901): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  901): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  901): acquireWL(4386fcf0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1249 1027 null
D/PMS     (  901): releaseWL(4386fcf0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  901): batLight: Full, plugged
V/LightsService(  901): setLight #8: color=#c8c800
D/qdlights(  901): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  901): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  901): setLight #8: color=#c800
D/qdlights(  901): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  901): [LedInfo] has indicator attribute
D/qdlights(  901): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  901): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AlarmManager(  901): ACTION_SCREEN_ON
I/AlarmManager(  901): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  901): [AlarmQueuing] done recovering
I/AlarmManager(  901): [AlarmQueuing] recover EPS screen off blocked alarms
,D/AutoSetting( 1398): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/WifiDataStallTracker(  901): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  901): startDataStallAlarm: tag=20269 delay=15s
,I/CheckinTask( 1225): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1225): Unable to close GMS GoogleHttpClient
I/AlarmManager(  901): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiNative-wlan0(  901): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiStateMachine(  901): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): SET_SCREEN_ON:On
I/wpa_supplicant( 1171): htc_wext_set_keepalive +
I/wpa_supplicant( 1171): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1171): getPrivFuncNum +	
I/wpa_supplicant( 1171): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1171): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1171): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  901):    returned true
,D/WifiNative-wlan0(  901): doBoolean: SignalStrength 97
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  901):    returned true
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1225/10028)
I/ClockThread( 1111): stop update clock
D/TetherSettings( 4279): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4279): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4279): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4279): Cust_ConnectToPC   : spcsc>false
D/        ( 4279): Cust_ConnectToPC   : IPT>true
,D/        ( 4279): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4279): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/SRS_Proc(  371): ParamSet string: screen_state=on
D/WirelessDisplayService(  901): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
E/SmartNS_Utility( 4279): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4279): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4279): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WIFI_ICON( 1111): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
V/NotificationService(  901): batLight: Full, plugged
V/LightsService(  901): setLight #8: color=#c8c800
D/qdlights(  901): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  901): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  901): setLight #8: color=#c800
D/qdlights(  901): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  901): [LedInfo] has indicator attribute
D/qdlights(  901): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  901): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/PSReceiver( 4279): onReceive:android.intent.action.USER_PRESENT
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/SmartNS_PSService( 4279): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4279): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4279):  defaultType:0
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4279): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/NetworkPolicy(  901): updateScreenOn: false
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1225/10028)
,D/PMS     (  901): releaseWL(4338d130): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 1225): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bd2238 that was originally bound here
E/ActivityThread( 1225): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bd2238 that was originally bound here
E/ActivityThread( 1225): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1225): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1225): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1225): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1225): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1225): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1225): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1225): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1225): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1225): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1225): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1225): 	at bks.a(SourceFile:298)
E/ActivityThread( 1225): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1225): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1225): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1225): 	at java.lang.Thread.run(Thread.java:864)
,I/ActivityManager(  901): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4811 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  901): acquireWL(4385ceb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1439 10028 null
,D/PMS     (  901): releaseWL(4385ceb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1808): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1808): onScreenOn: 1453102529117
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1808): onScreenOn: 1453102529117
,I/SensorManager(  901): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422deca0
W/SensorService(  901): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  901): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  901): pid=901, uid=1000
W/SensorService(  901): Active sensors: size = 2
W/SensorService(  901): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  901): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  901): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422deca0, eanble = 0, strlen(mName) = 91
W/SensorService(  901): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  901): Listener[0] = com.htc.smartdim.sensor_eye@4262c460
,W/SensorService(  901): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  901): goingToSleep
D/PMS     (  901): acquireWL(43886390): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 901 1000 null
D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
W/ContextImpl( 4811): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/PMS     (  901): releaseWL(43886390): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  901): ACTION_SCREEN_OFF
,I/AlarmManager(  901): [AlarmQueuing] screen off now: 
,I/AlarmManager(  901): [AlarmQueuing] data connection: true
,D/SmartSyncUtils( 4811): isEpsOn(), nState = 0
,I/AlarmManager(  901): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  901): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  901): stopDataStallAlarm: current tag=20269 mDataStallAlarmIntent=PendingIntent{42396460: PendingIntentRecord{424d8288 android broadcastIntent}}
D/WifiNative-wlan0(  901): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  901): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): SET_SCREEN_ON:Off
I/wpa_supplicant( 1171): htc_wext_set_keepalive +
I/wpa_supplicant( 1171): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1171): getPrivFuncNum +	
I/wpa_supplicant( 1171): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1171): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1171): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1171): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1171): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  901):    returned true
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  901): acquireWL(4260f1b8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4811 1000 null
D/PMS     (  901): acquireWL(43862c78): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 901 1000 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/NetworkPolicy(  901): updateScreenOn: false
,D/ContactMessageStore( 1238): start background delete task...
D/ContactMessageStore( 1238): size: 0 , 0
,D/ContactMessageStore( 1238): Background delete complete
D/PMS     (  901): releaseWL(4260f1b8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  901):    returned true
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/SmartSyncUtils( 4811): getMobilePolicyEnabled, result = true
D/PMS     (  901): releaseWL(43862c78): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,W/fb4a(:<default>):UserScope( 4605): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4605): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/Process (  901): killProcessQuiet, pid=4447
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  901): Killing 4447:com.htc.backup/1000 (adj 15): empty #17
D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
I/ActivityManager(  901): Recipient 4447
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GCM     ( 1364): GCM config loaded
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] getTotalRam: 1873 Mb
,D/SmartSyncUtils( 4811): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4811): getMobilePolicyEnabled, result = true
W/ContextImpl( 4811): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/SmartSyncUtils( 4811): isEpsOn(), nState = 0
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1808): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1808): onScreenOff
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1808): disableBatteryAlarm
D/WifiService(  901): New client listening to asynchronous messages
D/PMS     (  901): acquireWL(42c7dac0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1439 10028 null
,D/PMS     (  901): releaseWL(42c7dac0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1808): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1808): onScreenOff
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  901): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4262c460
W/SensorService(  901): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  901): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/AutoSetting( 1398): service - mHandler: cancel location update
,D/AutoSetting( 1398): service -           changes count: 0
W/SensorService(  901): pid=901, uid=1000
W/SensorService(  901): Active sensors: size = 1
W/SensorService(  901): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  901): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4262c460, eanble = 0, strlen(mName) = 36
W/SensorService(  901): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  901): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  901): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  901): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  901): pid=901, uid=1000
W/SensorService(  901): Active sensors: size = 0
W/SensorService(  901): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4262c460, eanble = 0, strlen(mName) = 36
W/SensorService(  901): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  901): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  901): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4262c460
E/ActivityThread(  901): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42386740 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  901): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42386740 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  901): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  901): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  901): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  901): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  901): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  901): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  901): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  901): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  901): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  901): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  901): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  901): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  901): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  901): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  901): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  901): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  901): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  901): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  901): 	at dalvik.system.NativeStart.main(Native Method)
,D/libc    (  901): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  901): [NET] getaddrinfo-,err=8
D/libc    (  901): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  901): [NET] getaddrinfo-, 1
,D/libc    (  901): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =f365 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,E/fb4a(:<default>):LocalFbBroadcastManager( 4605): Called registerBroadcastReceiver twice.
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  901): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  901): Find DNS Address www.htc.com/104.81.130.175
,D/PMS     (  901): releaseWL(43c654c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.facebook.katana (4605/10026)
,D/WifiStateMachine(  901): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  901): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  901): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  901): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC <<
,I/GAV2    ( 4687): Thread[GAThread,5,main]: No campaign data found.
,D/AutoSetting( 1507): service - handleMessage() stop self
,D/AutoSetting( 1507): service - onDestroy() END
,D/AutoSetting( 1507): service - handleMessage() quit looper
,D/Process (  901): killProcessQuiet, pid=4465
,I/ActivityManager(  901): Killing 4465:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  901): Recipient 4465
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV4    ( 4767): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  901): killProcessQuiet, pid=4411
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  901): Killing 4411:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  901): Recipient 4411
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  901): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  901): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  901): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  901): Waited long enough for: ServiceRecord{44219ce8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  901): acquireWL(438624c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): releaseWL(438624c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(435a0f28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{41d92378: PendingIntentRecord{42489e70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=133164, Int=0
,D/PMS     (  901): acquireWL(435a0908): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 901 1000 null
,D/PMS     (  901): releaseWL(435a0f28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4358af10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/PMS     (  901): releaseWL(435a0908): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  901): releaseWL(4358af10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1398): service - mHandler: update timezone
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  901): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1507): service - onCreate()
W/ActivityManager(  901): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1565): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  901): batLight: Full, plugged
V/LightsService(  901): setLight #8: color=#c8c800
D/qdlights(  901): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  901): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  901): setLight #8: color=#c800
D/qdlights(  901): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  901): [LedInfo] has indicator attribute
D/qdlights(  901): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  901): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1507): service - mHandler: update timezone
,D/AutoSetting( 1507): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1507): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1507): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1507): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/PhoneStatusBar( 1111): removeNotification.gc:52
,I/RemoteViews( 1111): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41b738f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.htc.htclocationservice 3 6 2 11
,D/AutoSetting( 1398): service - handleMessage() stop self
,D/AutoSetting( 1398): service - onDestroy() END
,D/AutoSetting( 1398): service - handleMessage() quit looper
,D/PMS     (  901): acquireWL(421be0a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=142443, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(421be0a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  901): killProcessQuiet, pid=3938
,I/ActivityManager(  901): Killing 3938:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  901): Recipient 3938
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  901): Waited long enough for: ServiceRecord{43ac23e0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  901): acquireWL(42eb3150): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10028}
,V/AlarmManager(  901): sending alarm PendingIntent{425fbb98: PendingIntentRecord{424d4b88 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141749, Int=0
,V/AlarmManager(  901): sending alarm PendingIntent{4239f110: PendingIntentRecord{4239f738 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141797, Int=0
,V/AlarmManager(  901): sending alarm PendingIntent{41d92378: PendingIntentRecord{42489e70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=163184, Int=0
,D/GpsLocationProvider(  901): ALARM_XTRA_TIMEOUT
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
D/PMS     (  901): acquireWL(422f8be0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 901 1000 null
D/PMS     (  901): acquireWL(4203db30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
D/PMS     (  901): acquireWL(435c8b18): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 901 1000 null
D/PMS     (  901): releaseWL(4203db30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  901): releaseWL(42eb3150): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/GpsLocationProvider(  901): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  901): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/PMS     (  901): acquireWL(4239df60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=3 [28][1][0]
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/libc    (  901): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  901): [NET] getaddrinfo-,err=8
D/libc    (  901): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  901): [NET] getaddrinfo-, 1
,D/libc    (  901): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =950f +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/PMS     (  901): acquireWL(42dbe540): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 901 1000 WorkSource{10106}
D/PMS     (  901): releaseWL(435c8b18): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  901): releaseWL(4239df60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/PMS     (  901): acquireWL(42655d30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
I/NewsWeather( 4767): Last usage 0, idle 1453102580s, sync interval 2592000s
,I/NewsWeather( 4767): setPeriodicSync in seconds 2592000
D/PMS     (  901): releaseWL(42655d30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 31
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  901): [NET] getaddrinfo_proxy-, success
I/global  (  901): call createSocket() return a new socket.
D/libc    (  901): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  901): [NET] getaddrinfo-, SUCCESS
,I/NewsWeather( 4767): Skip sync for lookup editions
,I/NewsWeather( 4767): syncNewsAppData traffic type BACKGROUND_POLL
,D/GpsLocationProvider(  901): [handleDownloadXtraData] calling native_inject_xtra_data
,I/NewsWeather( 4767): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1111): com.google.android.gms (false,0)
,E/NewsWeather( 4767): Unrecoverable authentication exception
E/NewsWeather( 4767): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4767): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4767): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4767): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41c369f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.google.android.gms 1 12 3 12
,D/PMS     (  901): acquireWL(42352990): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  901): releaseWL(42352990): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
E/NewsWeather( 4767): Failed to syncNewsAppData
,E/NewsWeather( 4767): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/PMS     (  901): acquireWL(424fb3d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/SyncManager(  901): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 110724, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  901): releaseWL(42dbe540): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/GpsLocationProvider(  901): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  901): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  901):  [handleDownloadXtraData]inject done.
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1439/10028)
D/PMS     (  901): releaseWL(424fb3d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/GpsLocationProvider(  901): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  901): acquireWL(42520048): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
D/PMS     (  901): releaseWL(42520048): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
,D/PMS     (  901): releaseWL(422f8be0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1507): service - handleMessage() stop self
,D/AutoSetting( 1507): service - onDestroy() END
,D/AutoSetting( 1507): service - handleMessage() quit looper
,D/Process (  901): killProcessQuiet, pid=4483
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  901): Killing 4483:com.htc.calendar/u0a13 (adj 15): empty #17
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  901): Recipient 4483
,D/PMS     (  901): acquireWL(42e0dd40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42e0dd40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  901): updateBatteryInfo
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1238): switchBindHtcMsgCursor: null
,D/PMS     (  901): acquireWL(425cd0b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(425cd0b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  901): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(441a1360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{41d92378: PendingIntentRecord{42489e70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=193284, Int=0
,D/PMS     (  901): acquireWL(425fbd60): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 901 1000 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): releaseWL(441a1360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(441bb358): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/PMS     (  901): releaseWL(425fbd60): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  901): releaseWL(441bb358): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  901): acquireWL(4233d1b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=202444, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(4233d1b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(43ddd4a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,D/PMS     (  901): acquireWL(4254fec0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 901 1000 null
,V/AlarmManager(  901): sending alarm PendingIntent{41d92378: PendingIntentRecord{42489e70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=225503, Int=0
,D/PMS     (  901): releaseWL(43ddd4a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4259a398): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=12 [48][6][0]
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  901): acquireWL(42847ba8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 901 1000 WorkSource{10106}
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/PMS     (  901): releaseWL(4254fec0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  901): releaseWL(4259a398): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(44151740): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/PMS     (  901): releaseWL(44151740): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4767): Last usage 0, idle 1453102643s, sync interval 2592000s
,I/NewsWeather( 4767): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4767): Skip sync for lookup editions
,I/NewsWeather( 4767): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4767): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1111): com.google.android.gms (false,0)
,E/NewsWeather( 4767): Unrecoverable authentication exception
E/NewsWeather( 4767): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4767): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4767): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4767): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41e0a000 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.google.android.gms 1 12 3 12
,E/NewsWeather( 4767): Failed to syncNewsAppData
,E/NewsWeather( 4767): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  901): acquireWL(42c882a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/PMS     (  901): acquireWL(43ce1070): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
D/PMS     (  901): releaseWL(42c882a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/SyncManager(  901): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 163601, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  901): releaseWL(42847ba8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1439/10028)
D/PMS     (  901): releaseWL(43ce1070): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/PMS     (  901): acquireWL(4237da18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
D/PMS     (  901): releaseWL(4237da18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
,D/PMS     (  901): acquireWL(43c9ec50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10026}
,V/AlarmManager(  901): sending alarm PendingIntent{424791d8: PendingIntentRecord{43b05048 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229013, Int=0
,I/ActivityManager(  901): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4857 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  901): sending alarm PendingIntent{425b13d0: PendingIntentRecord{42044de0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453102638669, Int=10800000
,D/PMS     (  901): releaseWL(43c9ec50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.htc.aurora (4857/10047)
,D/Process (  901): killProcessQuiet, pid=4497
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  901): Killing 4497:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  901): Recipient 4497
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.google.android.gms (1225/10028)
,D/PMS     (  901): acquireWL(42c63038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PowerUI ( 1111): closing low battery warning: level=100
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  901): releaseWL(42c63038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(43c2e598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10026}
,V/AlarmManager(  901): sending alarm PendingIntent{42b0b308: PendingIntentRecord{43b05048 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231604, Int=0
,D/PMS     (  901): releaseWL(43c2e598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  901): acquireWL(43868dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
D/UsbnetService(  901): BroadcastReceiver::onReceive+
,D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PMS     (  901): releaseWL(43868dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(42e22128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{41d92378: PendingIntentRecord{42489e70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=255565, Int=0
,D/PMS     (  901): acquireWL(432bb5c8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 901 1000 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): releaseWL(42e22128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(441f1d08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/PMS     (  901): releaseWL(432bb5c8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  901): releaseWL(441f1d08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  901): acquireWL(438925d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=262444, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(438925d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  901): acquireWL(4388a478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/PMS     (  901): releaseWL(4388a478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): closing low battery warning: level=100
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  901): acquireWL(43d73f48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(43d73f48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(439d36a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=322444, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(439d36a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4540): TAP version 13
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # multiplex can send data
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 1 String should be length:200
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # basic
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 2 sane
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # another
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 3 sane
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 4 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 5 null,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 6 (unnamed assert),
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 7 should be equal,
I/jxcore-log( 4540): 
I/jxcore-log( 4540): ok 8 should not throw
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # successfully read a previous pkcs12 file and return hash value,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 9 (unnamed assert)
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 10 (unnamed assert)
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 11 should not throw
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 12 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 13 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 14 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # failed to get mobile documents path,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 15 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 16 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 17 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 18 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # #init should register the networkChanged event
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 19 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # #startBroadcasting should throw on null device name,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 20 should throw,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 21 should throw
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # #startBroadcasting should throw on non-number port
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 22 should throw
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # #startBroadcasting should throw on NaN port
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 23 should throw
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # #startBroadcasting should throw on negative port
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 24 should throw
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # #startBroadcasting should throw on too large port
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 25 should throw
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 26 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 27 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 28 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 29 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 30 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 31 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 32 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 33 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 34 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 35 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 36 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 37 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 38 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 39 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 40 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # should call Mobile("Disconnect") without an error
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 41 should be equal,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 42 should be equal,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # should call Mobile("Disconnect") and handle an error,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 43 should be equal
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): ok 44 should be equal,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # setup,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error,
I/jxcore-log( 4540): 
,I/jxcore-log( 4540): # teardown
I/jxcore-log( 4540): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4540): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4540): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  901): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4540): start: Peer ID: 80:01:84:8A:B3:68, peer name: 1453102757995.4540
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4540): bind: Binding a new listener
,D/BluetoothManagerService(  901): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4540): initialize: My bluetooth address is 80:01:84:8A:B3:68
,D/BluetoothManagerService(  901): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4540): verifyIdentityString: Identity string created: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"1453102757995.4540"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4540): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  901): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 4540): getBluetoothService(): entry
,W/BluetoothAdapter( 4540): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1593): SOCK FLAG = 0 ***********************
I/bt-btif ( 1593): BTA_JvCreateRecordByUser
,D/bt-btm  ( 1593): BTM_AllocateSCN
D/bt-sdp  ( 1593): SDP_CreateRecord ok, num_records:17
I/bt-btif ( 1593): BTA_JvRfcommStartServer
,I/bt-btm  ( 1593): BTM_SEC_REG[19]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
,I/bt-btm  ( 1593):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4540): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4540): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4540): start: OK
,I/io.jxcore.node.ConnectionHelper( 4540): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  901): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4540): start: Peer ID: 80:01:84:8A:B3:68, peer name: 1453102757995.4540
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4540): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 4540): bind: Binding a new listener
,W/dalvikvm( 4540): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4540): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4540): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
,W/dalvikvm( 4540): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed,
W/dalvikvm( 4540): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4540): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
E/dalvikvm( 4540): Could not find class 'org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>
,W/dalvikvm( 4540): VFY: unable to resolve new-instance 427 (Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
W/dalvikvm( 4540): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
W/dalvikvm( 4540): VFY: unable to resolve virtual method 90: Landroid/bluetooth/le/ScanResult;.getScanRecord ()Landroid/bluetooth/le/ScanRecord;
E/dalvikvm( 4540): Could not find class 'android.bluetooth.le.AdvertiseSettings$Builder', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.applySettings
,W/dalvikvm( 4540): VFY: unable to resolve new-instance 20 (Landroid/bluetooth/le/AdvertiseSettings$Builder;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;,
W/dalvikvm( 4540): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
W/dalvikvm( 4540): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
W/dalvikvm( 4540): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4540): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4540): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4540): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4540): VFY: unable to resolve virtual method 1808: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.start ()Z
W/dalvikvm( 4540): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4540): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4540): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4540): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4540): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4540): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
,W/dalvikvm( 4540): VFY: unable to resolve virtual method 1809: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.stop ()V
W/dalvikvm( 4540): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4540): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4540): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
,W/dalvikvm( 4540): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
,D/BluetoothManagerService(  901): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/dalvikvm( 4540): threadid=1: thread exiting with uncaught exception (group=0x416b3e30)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): Uncaught exception: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): java.lang.NoClassDefFoundError: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>(BlePeerDiscoverer.java:60)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.startBlePeerDiscovery(DiscoveryManager.java:488)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:248)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:292)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): 	at io.jxcore.node.JXcoreExtension$6.Receiver(JXcoreExtension.java:177)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): 	at android.os.Handler.handleCallback(Handler.java:733)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): 	at android.os.Looper.loop(Looper.java:157)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4540): 	at dalvik.system.NativeStart.main(Native Method)
,D/PMS     (  901): acquireWL(439ff0a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,D/PMS     (  901): acquireWL(43a16c18): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 901 1000 null
,V/AlarmManager(  901): sending alarm PendingIntent{41d92378: PendingIntentRecord{42489e70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=346449, Int=0
D/PMS     (  901): releaseWL(439ff0a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(43672780): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/PMS     (  901): releaseWL(43a16c18): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  901): releaseWL(43672780): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  901): acquireWL(43ad4e60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(43ad4e60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1364): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1364): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1364): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1364): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1364): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1364): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1111): com.google.android.gms (false,0)
,E/PlayEventLogger( 4222): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4222): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4222): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4222): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4222): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4222): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4222): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4222): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41e79f98 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.google.android.gms 1 9 4 12
,D/libc    ( 4222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4222): [NET] getaddrinfo-,err=8
D/libc    ( 4222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4222): [NET] getaddrinfo-, 1
,D/libc    ( 4222): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8947 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4222): [NET] getaddrinfo_proxy-, success
I/global  ( 4222): call createSocket() return a new socket.
D/libc    ( 4222): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4222): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4222): [NET] getaddrinfo-,err=8
,D/PMS     (  901): acquireWL(42c4f800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42c4f800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  901): acquireWL(429b5950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{41d92378: PendingIntentRecord{42489e70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=376473, Int=0
,D/PMS     (  901): acquireWL(425b4498): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 901 1000 null
D/PMS     (  901): releaseWL(429b5950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(43a65860): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=7 [156][11][0]
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  901): acquireWL(439ff5b8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 901 1000 WorkSource{10106}
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/PMS     (  901): releaseWL(425b4498): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  901): releaseWL(43a65860): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4394a058): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/PMS     (  901): releaseWL(4394a058): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4767): Last usage 0, idle 1453102794s, sync interval 2592000s
,I/NewsWeather( 4767): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4767): Skip sync for lookup editions
,I/NewsWeather( 4767): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4767): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1111): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41b943f8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/NewsWeather( 4767): Unrecoverable authentication exception
E/NewsWeather( 4767): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4767): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4767): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
,E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4767): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews.Performance( 1111): com.google.android.gms 3 18 7 12
,D/PMS     (  901): acquireWL(42c85510): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  901): releaseWL(42c85510): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4767): Failed to syncNewsAppData
,E/NewsWeather( 4767): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/PMS     (  901): acquireWL(43941508): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/SyncManager(  901): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 225884, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  901): releaseWL(439ff5b8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/PMS     (  901): releaseWL(43941508): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (1439/10028)
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(42874448): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  901): releaseWL(42874448): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
,D/PMS     (  901): acquireWL(43d035c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=382444, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(43d035c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  901): acquireWL(43d0f950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{41d92378: PendingIntentRecord{42489e70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=406537, Int=0
,D/PMS     (  901): acquireWL(4294eb70): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 901 1000 null
,D/PMS     (  901): releaseWL(43d0f950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(425f7498): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/PMS     (  901): releaseWL(4294eb70): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  901): releaseWL(425f7498): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  901): acquireWL(43549388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(43549388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  901): updateBatteryInfo
,D/PowerUI ( 1111): closing low battery warning: level=100
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  901): acquireWL(436e31b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): releaseWL(436e31b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(4380e9b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=442443, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(4380e9b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  901): acquireWL(43169770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/PMS     (  901): releaseWL(43169770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  901): acquireWL(42624350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42624350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  901): acquireWL(441d07d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=502443, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(441d07d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  901): acquireWL(435c4f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PMS     (  901): releaseWL(435c4f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  901): acquireWL(43079c70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(43079c70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(42e38a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=562443, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(42e38a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(43ccc358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(43ccc358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  901): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  353): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  901): acquireWL(43cfb748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=622444, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(43cfb748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1238): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1238): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1238): sku_id=99
D/ContactMessageStore( 1238): start background delete task...
,D/ContactMessageStore( 1238): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1238): size: 0 , 0
,D/ContactMessageStore( 1238): Background delete complete
,D/PMS     (  901): acquireWL(432cdb30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10026}
,V/AlarmManager(  901): sending alarm PendingIntent{43772880: PendingIntentRecord{42627898 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=411340, Int=300000
,V/AlarmManager(  901): sending alarm PendingIntent{41d92378: PendingIntentRecord{42489e70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=624543, Int=0
,V/AlarmManager(  901): sending alarm PendingIntent{43d8e380: PendingIntentRecord{425123c8 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1453102860629, Int=1800000
,D/PMS     (  901): acquireWL(43cdf368): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 901 1000 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(436e4cc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/PMS     (  901): acquireWL(42c5fba0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1225 10028 null
,D/PMS     (  901): releaseWL(432cdb30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  901): acquireWL(42b52d18): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1225 10028 null,
,D/PMS     (  901): releaseWL(42c5fba0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
I/EventLogService( 1225): Aggregate from 1453102526504 (log), 1453101060558 (data)
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=3 [33][1][0]
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  901): acquireWL(4389b3a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 901 1000 WorkSource{10106}
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/PMS     (  901): releaseWL(43cdf368): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  901): releaseWL(436e4cc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(43580100): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,I/NewsWeather( 4767): Last usage 0, idle 1453103042s, sync interval 2592000s
,I/NewsWeather( 4767): setPeriodicSync in seconds 2592000
D/PMS     (  901): releaseWL(43580100): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  901): releaseWL(42b52d18): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,I/NewsWeather( 4767): Skip sync for lookup editions
,I/NewsWeather( 4767): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4767): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1111): com.google.android.gms (false,0)
,E/NewsWeather( 4767): Unrecoverable authentication exception
E/NewsWeather( 4767): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4767): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4767): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4767): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41efb0c0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 4767): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4767): [NET] getaddrinfo-,err=8
D/libc    ( 4767): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4767): [NET] getaddrinfo-, 1
,D/libc    ( 4767): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b226 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
I/RemoteViews.Performance( 1111): com.google.android.gms 3 12 3 12
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4767): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 4767): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4767): [NET] getaddrinfo-,err=8
,E/NewsWeather( 4767): Failed to syncNewsAppData
,E/NewsWeather( 4767): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  901): acquireWL(43cd4038): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
D/PMS     (  901): releaseWL(43cd4038): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/SyncManager(  901): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 376935, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/PMS     (  901): acquireWL(43c87358): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
D/PMS     (  901): releaseWL(4389b3a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/PMS     (  901): releaseWL(43c87358): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (1439/10028)
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(435a5050): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/PMS     (  901): releaseWL(435a5050): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
,D/PMS     (  901): acquireWL(431e9648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): releaseWL(431e9648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(42e187c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{41d92378: PendingIntentRecord{42489e70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=654622, Int=0
,D/PMS     (  901): acquireWL(42e0caf8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 901 1000 null
D/PMS     (  901): releaseWL(42e187c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(42e09b18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/PMS     (  901): releaseWL(42e0caf8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  901): releaseWL(42e09b18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  901): acquireWL(42844f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42844f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(42844ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=682443, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(42844ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(42588720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10073}
,V/AlarmManager(  901): sending alarm PendingIntent{4374b398: PendingIntentRecord{42500ff8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453103102016, Int=0
,D/PMS     (  901): releaseWL(42588720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4222): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4222): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4222): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4222): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4222): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,D/PMS     (  901): acquireWL(422499d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10073}
,V/AlarmManager(  901): sending alarm PendingIntent{421b2fd0: PendingIntentRecord{42cd48e8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453103117246, Int=0
,D/PMS     (  901): releaseWL(422499d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4222): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  901): acquireWL(4265e498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
,D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  901): updateBatteryInfo
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  901): releaseWL(4265e498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/Process (  901): killProcessQuiet, pid=4107
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  901): Killing 4107:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  901): Recipient 4107
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  901): acquireWL(42583520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
D/UsbnetService(  901): BroadcastReceiver::onReceive+
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  901): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  901): releaseWL(42583520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(423d7d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=742444, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(423d7d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(425e2000): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(425e2000): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(4373f7f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=802443, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(4373f7f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(42468320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  901): updateBatteryInfo
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
D/PMS     (  901): releaseWL(42468320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  901): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(425091a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=862443, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(425091a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(43cfc5c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
I/BatteryService(  901): n_update end
,D/PowerUI ( 1111): closing low battery warning: level=100
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): releaseWL(43cfc5c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(43594bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10026}
,V/AlarmManager(  901): sending alarm PendingIntent{43772880: PendingIntentRecord{42627898 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=711340, Int=300000
,V/AlarmManager(  901): sending alarm PendingIntent{41dc3fe0: PendingIntentRecord{42421dc8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785516, Int=0
,I/ActivityManager(  901): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4908 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  901): sending alarm PendingIntent{43104d48: PendingIntentRecord{43921ea8 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,D/ConnectivityService(  901): Sampling interval elapsed, updating statistics ..
,D/PMS     (  901): releaseWL(43594bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  901): Done.
,D/ConnectivityService(  901): Setting timer for 720seconds
,I/ImageRamCache( 4908): create image Cache, size: 31457280.
I/ImageRamCache( 4908): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4908): create image Cache, size: 12582912.
,I/FeedSettings( 4908): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 4908): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4908): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4908): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4908): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4908): loadGridSize() with Alternative
,D/libc    ( 4908): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4
D/libc    ( 4908): [NET] getaddrinfo-,err=8
D/libc    ( 4908): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 4908): [NET] getaddrinfo-, 1
,D/libc    ( 4908): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =f28f +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=206
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4908): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.htc.launcher (4908/10075)
,D/ConnectivityService(  901): getActiveNetworkInfo called by com.htc.launcher (4908/10075)
,D/Process (  901): killProcessQuiet, pid=4583
,D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  901): Killing 4583:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/ActivityManager(  901): Recipient 4583
,I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  901): acquireWL(43501c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/PMS     (  901): releaseWL(43501c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  901): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  901): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  901): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(44205b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=922444, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(44205b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(43c55ac8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  901): BroadcastReceiver::onReceive-
,D/HeadsetPhoneState( 1593): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
V/NotificationService(  901): batLight: plugged
V/LightsService(  901): setLight #8: color=#c8c800
D/qdlights(  901): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  901): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  901): setLight #8: color=#c80000
D/qdlights(  901): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  901): [LedInfo] has indicator attribute
D/DotMatrix( 1565): [EventService] reorderNotification, total:1
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/qdlights(  901): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  901): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): releaseWL(43c55ac8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=98
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  901): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/ContextImpl( 4811): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4279): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4279): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4279): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4279): Cust_ConnectToPC   : spcsc>false
D/        ( 4279): Cust_ConnectToPC   : IPT>true
D/        ( 4279): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4279): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4279): Index of the first 1 = -1
W/Settings( 4279): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4279): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4279): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4279): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
W/ContextImpl( 4279): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4279): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 4279): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1111): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(425cb6e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(425cb6e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(43e36438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
,D/UsbnetService(  901): onReceive BATTERY_CHANGED
,I/BatteryService(  901): n_update end
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  901): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): releaseWL(43e36438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=98
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  901): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(425ff8c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=982443, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(425ff8c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(44219a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{10028}
,V/AlarmManager(  901): sending alarm PendingIntent{4357d148: PendingIntentRecord{424d6d78 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1010346, Int=0
D/PMS     (  901): acquireWL(425c7bd8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1364 10028 null
,V/AlarmManager(  901): sending alarm PendingIntent{425442b0: PendingIntentRecord{425dc5f0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453103358851, Int=900000
,V/AlarmManager(  901): sending alarm PendingIntent{42570fb0: PendingIntentRecord{441dc2a0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453103429288, Int=0
,D/PMS     (  901): releaseWL(425c7bd8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  901): acquireWL(43c87220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  901): releaseWL(43c87220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/ContextImpl( 4811): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4811): call getInstance()
,D/SmartSyncUtils( 4811): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4811): MY_DEBUG = false
D/PMS     (  901): acquireWL(42595568): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4811 1000 null
D/PMS     (  901): releaseWL(44219a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4811): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4811): [updateNmRange] USERNIGHT_TIMESTART = 20, USERNIGHT_TIMEEND = 23, nStart = 1, nEnd = 2, bNormalRange = true
,W/BatSI   (  901): Couldn't get kernel wake lock stats
,D/PMS     (  901): acquireWL(433600a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10028 null
,D/GCM     ( 1364): Message class mow
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
D/ConnectivityService(  901): reportInetCondition for net 1, percentage: 100 by  (1364/10028)
D/ConnectivityService(  901): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  901): handleInetConditionChange: starting a change hold
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1364/10028)
,D/PMS     (  901): releaseWL(433600a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  901): acquireWL(43c7bf28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  901): releaseWL(43c7bf28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/SmartSyncScreenOnOffTimeReceiver( 4811): [updateNmRange] new USERNIGHT_TIMESTART = 1, new USERNIGHT_TIMEEND = 2
,I/FeedHostManager( 1262): onReceive() -- Intent { act=com.htc.powersaver.SMARTSYNC_SLEEPMODE_TIME_UPDATE flg=0x10 }
,I/FeedHostManager( 1262): NightMode begin at 0, end at 7
W/ContextImpl( 4811): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.updateNmRange:2650 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.SettingPowerModeAlarm:972 
,D/PMS     (  901): acquireWL(4265b130): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1262 10075 null
D/SmartSyncScreenOnOffTimeReceiver( 4811): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 4811): SettingOnTime = 1453165200000, randomSettingOnTime = 1453162132000
,D/SmartSyncScreenOnOffTimeReceiver( 4811): SettingOffTime = 1453161600000, randomSettingOffTime = 1453161600000
,D/SmartSyncScreenOnOffTimeReceiver( 4811): bDayMode = false
,I/FeedHostManager( 1262): scheduleNextNightModeAlarm - today's NightMode - CurrentTime: 1453103429467, BeginTime: 1453158000000, EndTime: 1453183200000
D/SmartSyncScreenOnOffTimeReceiver( 4811): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4811): bNightModeTurnOffOnce = false
D/PMS     (  901): releaseWL(4265b130): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
D/PMS     (  901): releaseWL(42595568): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  901): Couldn't get kernel wake lock stats
,W/BatSI   (  901): Couldn't get kernel wake lock stats
,W/BatSI   (  901): Couldn't get kernel wake lock stats
,D/ConnectivityService(  901): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  901): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=9 [55][5][0]
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/PMS     (  901): acquireWL(441ea4e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
D/UsbnetService(  901): BroadcastReceiver::onReceive+
,D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): closing low battery warning: level=98
D/HtcPowerSaver(  901): updateBatteryInfo
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PMS     (  901): releaseWL(441ea4e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  901): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(43d51e88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1042443, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(43d51e88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(43d3e6b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
,D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
D/PMS     (  901): releaseWL(43d3e6b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PowerUI ( 1111): closing low battery warning: level=98
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/HtcPowerSaver(  901): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(438ea0c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1102444, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(438ea0c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(438a8308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{41d92378: PendingIntentRecord{42489e70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1120253, Int=0
,D/PMS     (  901): acquireWL(438a8188): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 901 1000 null
,D/PMS     (  901): releaseWL(438a8308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(43898470): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [9][0][0]
,D/WifiNative-wlan0(  901): doString: SIGNAL_POLL
,W/WifiHW  (  901): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/PMS     (  901): acquireWL(435b7de0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 901 1000 WorkSource{10106}
,D/PMS     (  901): releaseWL(438a8188): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  901): releaseWL(43898470): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(435a0f28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/PMS     (  901): releaseWL(435a0f28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4767): Last usage 0, idle 1453103537s, sync interval 2592000s
,I/NewsWeather( 4767): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4767): Skip sync for lookup editions
,I/NewsWeather( 4767): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4767): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1364): GoogleAccountDataService.getToken()
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1364): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1364): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 4767): Unrecoverable authentication exception
E/NewsWeather( 4767): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4767): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4767): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4767): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4767): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews( 1111): com.google.android.gms (false,0)
,D/libc    ( 4767): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4767): [NET] getaddrinfo-,err=8
D/libc    ( 4767): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
,D/libc    ( 4767): [NET] getaddrinfo-, 1
,D/libc    ( 4767): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =e14f +++++
D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{4201ff08 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4767): [NET] getaddrinfo_proxy-, success
,I/RemoteViews.Performance( 1111): com.google.android.gms 1 11 6 12
,D/libc    ( 4767): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4767): [NET] getaddrinfo-,err=8
,D/PMS     (  901): acquireWL(423675c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10028 null
,D/PMS     (  901): releaseWL(423675c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4767): Failed to syncNewsAppData
,E/NewsWeather( 4767): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(4229ef68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/SyncManager(  901): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 625039, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  901): releaseWL(435b7de0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  901): getActiveNetworkInfo called by  (1439/10028)
D/PMS     (  901): releaseWL(4229ef68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
D/PMS     (  901): acquireWL(41f495f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/PMS     (  901): releaseWL(41f495f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
,D/PMS     (  901): acquireWL(42399328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{41d92378: PendingIntentRecord{42489e70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1150311, Int=0
,D/PMS     (  901): acquireWL(422a1f60): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 901 1000 null
,D/PMS     (  901): releaseWL(42399328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  901): getActiveNetworkInfo called by  (901/1000)
,D/PMS     (  901): acquireWL(42eb0670): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 901 1000 null
,D/PMS     (  901): releaseWL(422a1f60): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  901): releaseWL(42eb0670): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  901): acquireWL(42c7dfe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(42c7dfe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(42657750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  901): releaseWL(42657750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1111): closing low battery warning: level=99
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
,I/HtcPowerSaver(  901): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  901): acquireWL(424af0c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1162443, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(424af0c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(41ffe3c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/UsbnetService(  901): BroadcastReceiver::onReceive+
D/UsbnetService(  901): onReceive BATTERY_CHANGED
D/UsbnetService(  901):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  901): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  901): releaseWL(41ffe3c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  901): updateBatteryInfo
D/PMS     (  901): runPSCheck
D/HtcPowerSaver(  901): Checking...
I/HtcPowerSaver(  901): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=99
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  901): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  901): << updateStatus
,W/AppWidgetServiceImpl(  901): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:2 level:99 unsupport:false plugged:true
,E/PNP_UPDATERD(  353): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  901): acquireWL(424b1518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(424b1518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(4384e868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1222444, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(4384e868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  901): acquireWL(4265bcc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  901): n_update end
,D/PMS     (  901): releaseWL(4265bcc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  901): acquireWL(42c74858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 901 1000 WorkSource{1000}
,V/AlarmManager(  901): sending alarm PendingIntent{42366740: PendingIntentRecord{423650a8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1282443, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  901): releaseWL(42c74858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4942): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4942): ====startRecUseTime====
D/htc.customization.log.level( 4942):  is 
W/CustomizationLogLevel( 4942): Level value is invalid, use default level 2
D/CustomizationManager( 4942):  Read ACC file spent 0.098 (s)
D/CIDMapFileReader( 4942): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4942): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4942): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4942): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4942): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4942): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4942): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4942): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4942): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4942): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4942): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4942): Parsing tag category name = system
I/CustomizationCIDLoader( 4942): Parsing tag category name = application
I/CustomizationCIDLoader( 4942): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4942): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4942): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4942): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4942): Parsing tag category name = Settings
D/CustomizationManager( 4942):  Read CID file spent 0.150 (s)
D/CustomizationManager( 4942):  All configurations done spent 0.150 (s)
W/HtcNativeFlag( 4942): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4942): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4942): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4942): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  901): deletePackageAsUser: pkg=com.test.thalitest, pid=4942, uid=2000 user=0
I/ActivityManager(  901): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
D/Process (  901): killProcessQuiet, pid=4540
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  901): Killing 4540:com.test.thalitest/u0a189 (adj 0): stop com.test.thalitest
W/ActivityManager(  901): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  901):   Force finishing activity ActivityRecord{423e2798 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  901): Copying FileAsset 0x65dbca58 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/InputDispatcher(  901): channel '420c92d8 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  901): channel '420c92d8 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  901): Attempted to unregister already unregistered input channel '420c92d8 com.test.thalitest.MainActivity (s)'
I/bt-btif ( 1593): BTA_JvDeleteRecord
I/bt-btif ( 1593): BTA_JvRfcommStopServer
D/bt-btm  ( 1593): BTM_FreeSCN 
D/bt-sdp  ( 1593): SDP_DeleteRecord ok, num_records:16
E/bt-btif ( 1593): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1593): BTM_SEC_CLR[19]: id 58
I/WindowManager(  901): WINDOW DIED Window{420c92d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  901): Client connection lost with reason: 4
W/WindowManager(  901): Failed looking up window
W/WindowManager(  901): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@42288d90 does not exist
W/WindowManager(  901): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  901): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  901): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  901): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  901): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  901): WIN DEATH: null
W/InputMethodManagerService(  901): Got RemoteException sending setActive(false) notification to pid 4540 uid 10189
W/Binder  ( 1203): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1203): java.lang.NullPointerException
W/Binder  ( 1203): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1203): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1203): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1203): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  901): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/dalvikvm-heap( 4257): Grow heap (frag case) to 15.197MB for 1821008-byte allocation
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1565): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1565): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1899): Unregistering com.test.thalitest
E/acms    ( 1899): Could not unregister removed application com.test.thalitest
W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 4908): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4908): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 1262): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1262): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/VoicemailCleanupService( 1289): Cleaning up data for package: com.test.thalitest
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "sms"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
D/PMS     (  901): acquireWL(43e9f580): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1439 10028 null
W/GeofencerStateMachine( 1439): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "smsto"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/Launcher( 1262): Deferring update until onResume
D/Launcher( 1262): waitUntilResume // bindAppsRemoved
D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  901): releaseWL(43e9f580): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "mms"
W/SystemReader( 1249): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/InputMethodManagerService(  901): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "mmsto"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
D/PackageBroadcastService( 1225): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "sms"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
E/ExternalAccountType( 1325): Unsupported attribute readOnly
I/ActivityManager(  901): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4958 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "smsto"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "mms"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  901):   Action: "android.intent.action.SENDTO"
I/PackageManager(  901):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  901):   Scheme: "mmsto"
I/PackageManager(  901): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4958): install
I/MultiDex( 4958): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4958): loading existing secondary dex files
I/MultiDex( 4958): load found 1 secondary dex files
I/MultiDex( 4958): install done
I/ActivityManager(  901): Delaying start of: ServiceRecord{43cbeac0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PeopleContactsSync( 1225): CP2 sync disabled
I/PackageManager(  901):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1225, uid=10028, userID:0
D/PMS     (  901): acquireWL(43da6370): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
I/ProviderInstaller( 4958): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/Icing   ( 1225): doRemovePackageData com.test.thalitest
D/PMS     (  901): releaseWL(43da6370): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  901): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4976 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  901): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4976): install
I/MultiDex( 4976): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4976): loading existing secondary dex files
I/MultiDex( 4976): load found 1 secondary dex files
I/ActivityManager(  901): Resuming delayed broadcast
I/MultiDex( 4976): install done
I/[PluginManager]RegisterService( 1398): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  901): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1398): handle notify Blinkfeed plugin client changed
I/ProviderInstaller( 4976): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  901): Resuming delayed broadcast
D/Process (  901): killProcessQuiet, pid=3915
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  901): Killing 3915:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Prism.PackageStateRece_( 1262): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2925): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  901): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4996 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  901): Recipient 3915
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  901): Client com.google.android.music (pid 3915): Died!
W/PackageManager(  901): Unable to load service info ResolveInfo{424cb5e8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  901): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  901): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  901): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  901): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  901): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  901): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  901): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  901): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  901): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  901): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  901): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  901): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  901): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  901): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  901): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  901): 	at dalvik.system.NativeStart.main(Native Method)
D/PMS     (  901): acquireWL(41afb038): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
E/SQLiteLog( 2925): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2925): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5ca57220
E/IcingCorporaProvider( 2925): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2925): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2925): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2925): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2925): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2925): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2925): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2925): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2925): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2925): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2925): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2925): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2925): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2925): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2925): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2925): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2925): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2925): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2925): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2925): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2925): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2925): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2925): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2925): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2925): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2925): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2925): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2925): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2925): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2925): 	... 15 more
W/IcingCorporaProvider( 2925): notifyTableChanged failed.
W/IcingCorporaProvider( 2925): Table change notification failed for TableStorageSpec[applications]
I/IcingCorporaProvider( 2925): UpdateCorporaTask done [took 188 ms] updated apps [took 188 ms] 
E/SQLiteLog( 4958): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4958): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca18ce0
D/PMS     (  901): releaseWL(41afb038): PARTIAL_WAKE_LOCK  Icing 0x1 null
E/DriveAsyncService( 4958): disk I/O error (code 3850)
E/DriveAsyncService( 4958): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4958): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4958): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4958): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4958): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4958): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4958): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4958): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4958): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4958): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4958): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4958): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4958): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4958): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4958): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4958): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 4958): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca18ce0
E/DocListDatabase( 4958): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4958): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4958): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4958): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4958): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4958): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4958): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4958): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4958): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4958): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4958): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4958): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4958): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4958): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4958): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4958): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4958): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4958): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4958): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4958): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4958): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4958): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4958): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4958): threadid=1: thread exiting with uncaught exception (group=0x416b3e30)
E/ActivityManager(  901): App crashed! Process: com.google.android.gms.drive
D/Process ( 4958): killProcess, pid=4958
D/Process ( 4958): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/AndroidRuntime( 4958): FATAL EXCEPTION: main
E/AndroidRuntime( 4958): Process: com.google.android.gms.drive, PID: 4958
E/AndroidRuntime( 4958): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4958): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4958): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4958): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4958): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4958): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4958): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4958): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4958): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4958): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4958): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4958): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4958): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4958): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4958): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4958): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4958): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4958): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4958): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4958): 	... 10 more
E/DropBoxManagerService(  901): Can't write: system_app_crash
E/DropBoxManagerService(  901): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  901): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  901): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  901): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  901): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  901): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  901): 	... 5 more
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  901): Recipient 4958
I/ActivityManager(  901): Process com.google.android.gms.drive (pid 4958) has died.
W/ActivityManager(  901): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
D/RemoteDisplayProvider(  901): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  901): start
W/AtomicFile(  901): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  901): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/SQLiteDatabase( 4996): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4996): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4996): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4996): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4996): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4996): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4996): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4996): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4996): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4996): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4996): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4996): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4996): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4996): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4996): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4996): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4996): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4996): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4996): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4996): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4996): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4996): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4996): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4996): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4996): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4996): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4996): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4996): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4996): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4996): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4996): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4996): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4996): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4996): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4996): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4996): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4996): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4996): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4996): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4996): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4996): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4996): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4996): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4996): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4996): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4996): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4996): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4996): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4996): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4996): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4996): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4996): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4996): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4996): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4996): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4996): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4996): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4996): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4996): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4996): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4996): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4996): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4996): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4996): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4996): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4996): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4996): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4996): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4996): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4996): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4996): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4996): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4996): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4996): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4996): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4996): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4996): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4996): threadid=11: thread exiting with uncaught exception (group=0x416b3e30)
E/ActivityManager(  901): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4996): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4996): Process: com.google.android.apps.docs, PID: 4996
E/AndroidRuntime( 4996): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4996): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4996): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4996): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4996): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4996): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4996): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4996): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4996): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  901): Can't write: system_app_crash
E/DropBoxManagerService(  901): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  901): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  901): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  901): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  901): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  901): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  901): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  901): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  901): 	... 5 more
E/SQLiteDatabase( 4996): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4996): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4996): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4996): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4996): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4996): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4996): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4996): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4996): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4996): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4996): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4996): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4996): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4996): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4996): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4996): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4996): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4996): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4996): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 4996): killProcess, pid=4996
D/Process ( 4996): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  901): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5017 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  901): Recipient 4996
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  901): Process com.google.android.apps.docs (pid 4996) has died.
W/ContextImpl( 5017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 5017): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5017): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5017): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5017): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5017): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5017): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5017): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5017): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5017): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5017): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5017): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5017): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5017): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5017): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5017): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5017): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5017): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5017): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5017): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5017): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5017): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5017): threadid=10: thread exiting with uncaught exception (group=0x416b3e30)
E/AndroidRuntime( 5017): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5017): Process: com.android.keychain, PID: 5017
E/AndroidRuntime( 5017): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5017): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5017): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5017): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5017): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5017): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5017): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5017): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5017): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5017): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5017): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5017): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5017): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5017): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5017): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5017): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5017): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5017): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5017): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5017): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  901): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5030 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  901): App crashed! Process: com.android.keychain
D/ErrorReport(  901): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 5017): killProcess, pid=5017
D/Process ( 5017): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  901): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  901): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453103732756.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  901): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  901): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  901): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  901): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  901): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  901): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  901): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  901): 	... 4 more
I/ActivityManager(  901): Recipient 5017
I/ActivityManager(  901): Process com.android.keychain (pid 5017) has died.
W/ActivityManager(  901): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10742ms
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AppTag  ( 5030): getInstance(Context context)
D/AppTag  ( 5030): getInstance(Context context)
D/AppTag  ( 5030): onCreate()
I/dalvikvm-heap( 4257): Grow heap (frag case) to 16.937MB for 1821008-byte allocation
I/ActivityManager(  901): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5046 uid=10098 gids={50098, 3003, 5012}
D/PMS     (  901): acquireWL(43da1068): PARTIAL_WAKE_LOCK  AsyncService 0x1 4257 10160 null
D/PMS     (  901): releaseWL(43da1068): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/DeviceManagement( 5046): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5046 dbg=false s=true
I/DeviceManagement( 5046): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5046): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5046): WorkflowService: Starting workflow service
I/DeviceManagement( 5046): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b0fdc0] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5046): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5046): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5046): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5046): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  901): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5062 uid=10099 gids={50099, 3003, 5012}
I/Prism.ItemManager( 4908): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4908): loadItems() com.htc.launcher.pageview.WidgetManager@41b519e8 +
I/Prism.WidgetManager( 4908): onLoadItems() +
I/Prism.ItemManager( 1262): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1262): loadItems() com.htc.launcher.pageview.WidgetManager@41b76dd8 +
I/Prism.WidgetManager( 1262): onLoadItems() +
I/DeviceManagement( 5046): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 5046): SessionStateController: Checking invariants...
D/Documents( 5062): Loading roots for com.android.providers.downloads.documents
D/Documents( 5062): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 5062): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5062): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5062): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5062): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5062): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5062): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5062): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5062): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5062): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5062): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5062): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5062): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5062): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5062): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5062): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5062): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5062): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5062): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5062): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5062): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5062): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5062): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5062): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5062): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5062): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5062): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5062): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5062): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5062): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5062): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5062): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5062): threadid=1: thread exiting with uncaught exception (group=0x416b3e30)
E/AndroidRuntime( 5062): FATAL EXCEPTION: main
E/AndroidRuntime( 5062): Process: com.android.documentsui, PID: 5062
E/AndroidRuntime( 5062): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5062): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5062): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5062): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5062): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5062): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5062): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5062): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5062): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5062): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5062): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5062): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5062): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5062): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5062): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5062): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5062): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5062): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5062): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5062): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5062): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5062): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5062): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5062): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5062): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5062): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5062): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5062): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5062): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5062): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5062): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5062): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5062): 	... 10 more
D/Process (  901): killProcessQuiet, pid=4634
D/Process (  901): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  901): Killing 4634:com.google.android.setupwizard/u0a78 (adj 15): empty #17
I/ActivityManager(  901): Recipient 4634
I/DisplayManagerService(  901): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/ActivityManager(  901): App crashed! Process: com.android.documentsui
I/ActivityManager(  901): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5076 uid=10023 gids={50023, 1028, 1015, 1023}
D/ErrorReport(  901): HtcErrorReportManager Begin---add error logs to dropbox
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
E/ErrorReport(  901): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  901): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453103733063.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  901): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  901): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  901): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  901): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  901): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  901): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  901): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  901): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  901): 	... 4 more

```
