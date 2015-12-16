#### Test 50650278923ff9f_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
E/cutils-trace( 4440): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4440): ====startRecUseTime====
D/htc.customization.log.level( 4440):  is 
W/CustomizationLogLevel( 4440): Level value is invalid, use default level 2
D/CustomizationManager( 4440):  Read ACC file spent 0.062 (s)
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4440): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4440): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4440): Parsing tag category name = system
I/CustomizationCIDLoader( 4440): Parsing tag category name = application
I/CustomizationCIDLoader( 4440): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4440): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4440): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4440): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4440): Parsing tag category name = Settings
D/CustomizationManager( 4440):  Read CID file spent 0.103 (s)
D/CustomizationManager( 4440):  All configurations done spent 0.103 (s)
W/HtcNativeFlag( 4440): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4440): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4440): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4440): Fail to get flag for type 'language', use default value: -1
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1129777680
--------- beginning of /dev/log/system
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4440
D/PMS     (  906): acquireHCC(43233000): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(4313fb00): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
I/FeedHostManager( 1269): [onPause]
I/FeedProviderManager( 1269): onPause
I/FeedHostManager( 1269): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c08f30
I/SocialFeedProvider( 1269): +onPause
D/PMS     (  906): acquireWL(42e15880): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/SocialFeedProvider( 1269): -onPause
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4451 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1269): [trimMemory] 20
,W/asset   ( 4451): Copying FileAsset 0x5c736420 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4451): Binding Chromium to main looper Looper (main, tid 1) {41ac0690}
I/LibraryLoader( 4451): Expected native library version number "",actual native library version number ""
I/chromium( 4451): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4451): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(4433a8b0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): acquireWL(44264128): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@434d1030:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  906): releaseWL(4433a8b0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4451): 1101881544: getState(). Returning 12
I/Adreno-EGL( 4451): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4451): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4451): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4451): Local Branch: 
I/Adreno-EGL( 4451): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4451): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4451):                  aa63bbd948f41d15fc72f585e
W/chromium( 4451): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4451): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4451): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4451): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4451): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4451): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4451): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4451): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4451): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4451): CordovaWebView is running on device made by: HTC
W/AwContents( 4451): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  906): Disable input method client, pid=1269
W/ResourceType( 4451): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4451): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b07778, mServedView=org.apache.cordova.engine.SystemWebView{41acd3e0 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  906): Enable input method client, pid=4451
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4451): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +464ms
D/PMS     (  906): releaseWL(42e15880): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4451): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4451): JniHelper::setJavaVM(0x41597048), pthread_self() = 1662312112
D/JX-Cordova( 4451): jxcore cordova android initializing
,D/PMS     (  906): acquireWL(43772100): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,D/PMS     (  906): releaseWL(43772100): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(436f92c0): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,D/PMS     (  906): releaseWL(436f92c0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(436e0ea8): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  906): releaseWL(436e0ea8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(4366b168): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,I/dalvikvm-heap( 4451): Grow heap (frag case) to 11.632MB for 144892-byte allocation
D/PMS     (  906): releaseWL(4366b168): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/dalvikvm-heap( 4451): Grow heap (frag case) to 11.739MB for 217334-byte allocation
,I/dalvikvm-heap( 4451): Grow heap (frag case) to 11.915MB for 325996-byte allocation
,I/dalvikvm-heap( 4451): Grow heap (frag case) to 12.189MB for 488990-byte allocation
,I/dalvikvm-heap( 4451): Grow heap (frag case) to 12.595MB for 733480-byte allocation
,I/dalvikvm-heap( 4451): Grow heap (frag case) to 14.101MB for 1650320-byte allocation
,I/dalvikvm-heap( 4451): Grow heap (frag case) to 15.460MB for 2475476-byte allocation
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(43233000): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
,D/PMS     (  906): releaseHCC(4313fb00): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4451): Grow heap (frag case) to 17.539MB for 3713210-byte allocation
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,W/jxcore-log( 4451): Initializing JXcore engine
,W/jxcore-log( 4451): JXcore engine is ready
,W/jxcore-log( 4451): Starting JXcore engine
,W/jxcore-log( 4451): Platform android
W/jxcore-log( 4451): 
,W/jxcore-log( 4451): Process ARCH arm
W/jxcore-log( 4451): 
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4500 uid=10077 gids={50077}
,D/PMS     (  906): acquireWL(435d26e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
V/AlarmManager(  906): sending alarm PendingIntent{421c06a0: PendingIntentRecord{4231fa38 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450280741293, Int=60000
,D/PMS     (  906): releaseWL(435d26e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4500): SMSBackupAgentService started
,D/SMSBackup( 4500): Checking restore status
D/SMSBackup( 4500): Restore complete
,D/SMSBackup( 4500): cancelCheckAlarm
D/SMSBackup( 4500): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  906): killProcessQuiet, pid=3670
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3670:com.htc.task/u0a70 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3670
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=136 rxSum=126} preTxRxSum={txSum=134 rxSum=124}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=19824 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19825 delay=15s
D/PMS     (  906): acquireWL(435a26a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{4342a9f0: PendingIntentRecord{423ccac8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=104892, Int=0
D/PMS     (  906): releaseWL(435a26a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4451): JXcore Cordova bridge is ready!
I/jxcore-log( 4451): 
,W/jxcore-log( 4451): JXcore engine is started
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/chromium( 4451): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  906): releaseWL(44264128): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4451): Toggling radios to true
I/jxcore-log( 4451): 
,D/BluetoothAdapter( 4451): enable(): BT is already enabled..!
,D/WifiManager( 4451): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 916
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
W/System.err(  906): java.lang.Throwable: stack dump
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
D/WifiManager( 4451): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
,D/WifiManager( 4451): reconnect: Base Package Name=com.test.thalitest, uid=10348
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): TDLS: Tear down peers
,I/wpa_supplicant( 1173): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4451): Radios toggled
I/jxcore-log( 4451): 
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  906): setWifiEnabled: true pid=4451, uid=10348
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,D/WifiService(  906): New client listening to asynchronous messages
I/jxcore-log( 4451): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4451): 
I/jxcore-log( 4451): Perf Test app loaded loaded
I/jxcore-log( 4451): 
I/Choreographer( 4451): Skipped 80 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4451): check test folder
I/jxcore-log( 4451): 
,I/jxcore-log( 4451): found test : ./testFindPeers.js
I/jxcore-log( 4451): 
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1173): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1173): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/wpa_supplicant( 1173): TDLS: Remove peers on disassociation
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1173): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1173): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1173): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1173): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb798ebc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1173):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1173): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1173): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1173): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1173): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1173): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1173): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1173): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1173,): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1173): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1173): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1173): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1173): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1173): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1173): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1173): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  906):    returned true
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED,
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false,
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  906): acquireWL(4359a490): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): Power_Mode_Type mode = 0
I/wpa_supplicant( 1173): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): Fast associate: Old scan results
I/jxcore-log( 4451): found test : ./testSendData.js
I/jxcore-log( 4451): 
I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19825 mDataStallAlarmIntent=PendingIntent{423c5930: PendingIntentRecord{423ccac8 android broadcastIntent}}
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): Power_Mode_Type mode = 0
I/wpa_supplicant( 1173): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1843/10178)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
D/UsbnetStateTracker(  906): isAvailable+-
D/WISPrService( 4233): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4233): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  906): New client listening to asynchronous messages
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  906): Exit handleNetworkDisconnect
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
,D/WISPrService( 4233): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4233): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] entry_id:6   entry:0xb8eba650  removed 
D/libc    (  363): [NET] entry_id:9   entry:0xb8ebad78  removed 
D/libc    (  363): [NET] entry_id:8   entry:0xb8ebabd8  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb8eba208  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb8ebaa20  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb8eba570  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb8eb58f0  removed 
D/libc    (  363): [NET] entry_id:10   entry:0xb8ebbf78  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb8ebee58  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8ebef68  removed 
D/libc    (  363): [NET] entry_id:11   entry:0xb8ebc120  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1843/10178)
D/PMS     (  906): acquireWL(42c8c270): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  906): acquireWL(42dbe750): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(423cbbc0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,D/PMS     (  906): releaseWL(42dbe750): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
I//system/bin/ip(  363): RTNETLINK answers: No such process
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
,D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1173): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  906):    returned false
D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  906): releaseWL(423cbbc0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1365/10028)
D/PMS     (  906): releaseWL(42c8c270): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
,I/chromium( 4451): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
,D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3,
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE,
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4342/10100)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): acquireWL(42b9d800): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1418/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1843/10178)
D/PMS     (  906): releaseWL(42b9d800): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/ConnectivityHelper( 1269): [onReceive] WIFI(1): DISCONNECTED,
,I/NetworkMonitor( 3905): type=WIFI subType= reason=null isConnected=false
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  906): NoActiveNetworkState
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1884/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10075)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3905/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4342/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1998/10021)
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4524 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4524): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4524): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4524): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4524): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4524): Preparing secondary program dexes.
V/DexLibLoader( 4524): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4524): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4524): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4524): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4524): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4524): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4524): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4524): Dex already copied
D/OdexVerifier( 4524): Odex verification is skipped.
,V/DexLibLoader( 4524): Creating class loader
,V/DexLibLoader( 4524): Finished creating class loader
V/DexLibLoader( 4524): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4524): Dex already copied
D/OdexVerifier( 4524): Odex verification is skipped.
,V/DexLibLoader( 4524): Creating class loader
,V/DexLibLoader( 4524): Finished creating class loader
V/DexLibLoader( 4524): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4524): Dex already copied
D/OdexVerifier( 4524): Odex verification is skipped.
V/DexLibLoader( 4524): Creating class loader
V/DexLibLoader( 4524): Finished creating class loader
V/DexLibLoader( 4524): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4524): Dex already copied
D/OdexVerifier( 4524): Odex verification is skipped.
,V/DexLibLoader( 4524): Creating class loader
,V/DexLibLoader( 4524): Finished creating class loader
,V/DexLibLoader( 4524): Verifying classes from secondary dexes.
,D/DexLibLoader( 4524): DexLibLoader.ensureDexLoaded took 27 ms
,I/SensorManager(  906): mEventCount = 900
,W/dalvikvm( 4524): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4524): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4524): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4524): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4524): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4524): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4524): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4524): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4524): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-76
I/wpa_supplicant( 1173): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
D/wpa_supplicant( 1173): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1173): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1173): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1173): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1173): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1173): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 3
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 1
I/wpa_supplicant( 1173): wpa_s->is_screen_on 1
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): selected network = 1
D/wpa_supplicant( 1173): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb79904e8  current_ssid=0x0
D/wpa_supplicant( 1173),: wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1173): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1173): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1173): check if in concurrent case
I/wpa_supplicant( 1173): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1173): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1173): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1173): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1173): RSN: PMKSA cache search - network_ctx=0xb79904e8 try_opportunistic=0
D/wpa_supplicant( 1173): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1173): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1173): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1173): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1173): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1173): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1173): nl80211: Unsubscribe mgmt frames handle 0xb798f718 (mode change)
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1173): nl80211: Subscribe to mgmt frames with non-AP handle 0xb798f718
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb798f718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb798f718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb798f718
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb798f718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb798f718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb798f718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb798f718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb798f718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb798f718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb798f718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1173):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1173):   * freq=2412
D/wpa_supplicant( 1173):   * Auth Type 0
D/wpa_supplicant( 1173):   * WPA Versions 0x2
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1173): nl80211: Connect request send successfully
D/wpa_supplicant( 1173): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd ,18
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=1 len=6
,I/wpa_supplicant( 1173): reply (631) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-48
I/wpa_supplicant( 1173): tsf=0000000021701273
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-55
I/wpa_supplicant( 1173): tsf=0000000108781055
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-79
I/wpa_supplicant( 1173): tsf=0000000108781063
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1173): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-55
I/wpa_supplicant( 1173): tsf=0000000108781051
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1173): ssid=01ABC
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2427
I/wpa_supplicant( 1173): level=-76
I/wpa_supplicant( 1173): tsf=0000000108781059
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 21701273, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 108781055, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -79, frequency: 2437, timestamp: 108781063, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 108781051, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2427, timestamp: 108781059, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,E/FbInjectorInitializer( 4524): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1173): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1173): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1173): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1173): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1173): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1173): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1173): nl80211: if_removed already cleared - ignore event
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
,D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1173): nl80211: Connect event
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1173): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1173): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1173): Add randomness: count=11 entropy=5
I/wpa_supplicant( 1173): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1173): TDLS: Remove peers on association
D/wpa_supplicant( 1173): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1173): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1173): EAPOL: enable timer tick
D/wpa_supplicant( 1173): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1173): htc_wext_set_keepalive +
I/wpa_supplicant( 1173): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1173): getPrivFuncNum +	
I/wpa_supplicant( 1173): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive fnum = 0x8bf6
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 1173): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1173): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1173): Get randomness: len=32 entropy=6
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChan,ge():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Associated
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
I/wpa_supplicant( 1173): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb798f9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1173):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1173): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1173): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f51b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1173):    broadcast key
D/WifiStateMachine(  906): This record is existed, only update it...
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1173): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1173): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1173): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1173): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1173): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1173): set send_ind_to_ndc = 0
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1173): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1173): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1173): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1173): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1173): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1173): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1173): EAPOL authentication completed successfully
I/wpa_supplicant( 1173): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1173): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/wpa_supplicant( 1173): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1173): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WISPrService( 4233): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4233): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/DhcpStateMachine(  906): [StoppedState] Start DHCP
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): Power_Mode_Type mode = 1
I/wpa_supplicant( 1173): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(42c875f8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiNative-wlan0(  906):    returned null
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42480df0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42480df0 target=com.android.internal.util.StateMachine$SmHandler }
,W/fb4a(:<default>):StaticBindingVerifier( 4524): Verify
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0,
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4524): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4524): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4524): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=3314
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3314:com.android.defcontainer/u0a19 (adj 15): empty #17
,D/PMS     (  906): acquireWL(430346b8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1223 10028 null
I/ActivityManager(  906): Recipient 3314
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(43fede88): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1223 10028 null
,D/PMS     (  906): releaseWL(430346b8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/GCM     ( 1365): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
D/PMS     (  906): releaseWL(43fede88): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/AutoSetting( 1404): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4553 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1404/10053)
,D/AutoSetting( 1404): Util - no network available!
,D/AutoSetting( 1404): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1404): service - mHandler: cancel location update
,D/AutoSetting( 1404): service -           changes count: 0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1404/10053)
,W/fb4a(:<default>):UserScope( 4524): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4524): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4553): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4553): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4553): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4553): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4524): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4567 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=4283
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 4283:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4553/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4553/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4553/10078)
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4283
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4524): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/WifiService(  906): Client connection lost with reason: 4
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4584 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3887
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3887:com.htc.mediamanager/u0a32 (adj 15): empty #17
,E/dalvikvm( 4524): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4524): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,I/dalvikvm-heap( 4524): Grow heap (frag case) to 9.961MB for 84664-byte allocation
E/dalvikvm( 4524): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4524): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4524): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4524): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4524): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4524): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4584): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4584): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4584): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4584): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4584): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4524): Grow heap (frag case) to 9.976MB for 28144-byte allocation
,W/dalvikvm( 4524): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4524): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4524): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 4524): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4524): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4524): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4524): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4524): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4524): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4524): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4524): Grow heap (frag case) to 10.018MB for 39954-byte allocation
,I/ActivityManager(  906): Recipient 3887
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4524): Grow heap (frag case) to 10.094MB for 79892-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4584/10151)
,V/WebViewChromiumFactoryProvider( 4584): Binding Chromium to main looper Looper (main, tid 1) {41ac5290}
,I/LibraryLoader( 4584): Expected native library version number "",actual native library version number ""
,I/chromium( 4584): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4584): Initializing chromium process, renderers=0
,D/PMS     (  906): acquireWL(42545f40): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  906): acquireWL(42922950): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4584): BLUETOOTH permission is missing!
D/PMS     (  906): releaseWL(42545f40): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4584): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4584): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4584): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4584): Local Branch: 
I/Adreno-EGL( 4584): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4584): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4584):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4584): Starting up...
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4584/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4584/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4208/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4208/10160)
,I/ActivityManager(  906): Killing 4053:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=4053
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/dalvikvm-heap( 4524): Grow heap (frag case) to 10.282MB for 75760-byte allocation
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1843/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1843/10178)
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44049360 u0 ReceiverList{44049240 4524 com.facebook.katana/10026/u0 remote:4401ec58}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44049360 u0 ReceiverList{44049240 4524 com.facebook.katana/10026/u0 remote:4401ec58}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42c85b70 u0 ReceiverList{42c85b10 4524 com.facebook.katana/10026/u0 remote:42c83b88}}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/PMS     (  906): acquireWL(43a33e60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1418 10028 null
,D/PMS     (  906): releaseWL(43a33e60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): acquireWL(43221368): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1418 10028 null
,D/GCoreFlp( 1418): Unknown pending intent to remove.
D/PMS     (  906): releaseWL(43221368): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  906): Recipient 4053
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 1173): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1173): EAPOL: disable timer tick
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4524): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4524): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421749a0
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  906): setLight #0: color=#0
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421749a0, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42314e18
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@425fa8d0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/PMS     (  906): mWirelessDisplayManager is null
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 387ms
,D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4319db50)
,D/NfcService( 1255): ScreenObserver: OFF
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
W/ResourceType( 4451): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4451): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41acd3e0 VFEDH.C. .F...... 0,0-720,1134 #64}
,D/NfcService( 1255): applyRouting - 0
D/PMN     (  906): wakingUp
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
I/InputMethodManagerService(  906): Disable input method client, pid=4451
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
,I/WindowManager(  906): No lock screen! windowToken=null
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/NfcService( 1255): applyRouting -2
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): acquireWL(430b9fd0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMS     (  906): acquireWL(4310d6b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/PMN     (  906): onScreenOn
D/PMS     (  906): releaseWL(430b9fd0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4310d6b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/MtpService( 1998): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 1998): [MTP][onReceive]-
,D/NfcService( 1255): applyRouting - 0
,D/NfcService( 1255): applyRouting -2
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): acquireWL(43f70d30): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
,D/PMS     (  906): releaseWL(43f70d30): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/AutoSetting( 1404): receiver - intent: android.intent.action.USER_PRESENT
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,D/AutoSetting( 1404): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): SET_SCREEN_ON:On
I/wpa_supplicant( 1173): htc_wext_set_keepalive +
I/wpa_supplicant( 1173): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1173): getPrivFuncNum +	
I/wpa_supplicant( 1173): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
V/SRS_Proc(  371): ParamSet string: screen_state=on
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
,I/ClockThread( 1117): stop update clock
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/TetherSettings( 4233): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4233): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4233): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4233): Cust_ConnectToPC   : spcsc>false
D/        ( 4233): Cust_ConnectToPC   : IPT>true
,D/        ( 4233): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4233): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,D/NetworkPolicy(  906): updateScreenOn: false
E/SmartNS_Utility( 4233): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4233): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4233): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4233): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 4233): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4233): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4233): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4233):  defaultType:0
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4657 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  906): acquireWL(41cacbd0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1418 10028 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1808): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1808): onScreenOn: 1450280747317
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1808): onScreenOn: 1450280747317
D/PMS     (  906): releaseWL(41cacbd0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42314e18
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42314e18, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@425fa8d0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1173): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(43095ea8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  906): releaseWL(42c875f8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/PMS     (  906): releaseWL(43095ea8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): gateway: /192.168.1.1
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19826 mDataStallAlarmIntent=null
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): SET_SCREEN_ON:Off
I/wpa_supplicant( 1173): htc_wext_set_keepalive +
,I/wpa_supplicant( 1173): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1173): getPrivFuncNum +	
I/wpa_supplicant( 1173): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1173): get_ip_address source addr = c0a80176,
I/wpa_supplicant( 1173): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1173): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -55, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(4317ec68): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  906): WAN detection
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
W/ContextImpl( 4657): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/WISPrService( 4233): >>>>>WISPrService start isConnected = true<<<<<
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@423eecb0
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  906): updateScreenOn: false
D/PMS     (  906): releaseWL(4317ec68): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/PMS     (  906): acquireWL(4403dd30): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4657 1000 null
,D/SmartSyncUtils( 4657): isEpsOn(), nState = 0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [1][0][0]
,I/wpa_supplicant( 1173): Change stage from stage0 to stage3
D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [1][0][0]
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  906): acquireWL(4409cb70): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4553/10078)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(4403dd30): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4657): getMobilePolicyEnabled, result = true
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/ContactMessageStore( 1242): start background delete task...
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/ContactMessageStore( 1242): size: 0 , 0
D/ContactMessageStore( 1242): Background delete complete
,D/Process (  906): killProcessQuiet, pid=4312
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Killing 4312:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
W/ContextImpl( 4657): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4657): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4657): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4657): isEpsOn(), nState = 0
I/ActivityManager(  906): Recipient 4312
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): New client listening to asynchronous messages
,D/AutoSetting( 1404): service - mHandler: cancel location update
,D/AutoSetting( 1404): service -           changes count: 0
,D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] getTotalRam: 1873 Mb
D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1808): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1808): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1808): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1808): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1808): onScreenOff
D/PMS     (  906): acquireWL(43493d10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1418 10028 null
D/PMS     (  906): releaseWL(43493d10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(4409cb70): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425fa8d0
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425fa8d0, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425fa8d0, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425fa8d0
D/PMS     (  906): acquireWL(43670238): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1223 10028 null
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425fae18 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425fae18 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1843/10178)
I/CheckinService( 1223): Preparing to send checkin request
,I/EventLogService( 1223): Accumulating logs since 1450280690762
D/PMS     (  906): acquireWL(435e4d50): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1223 10028 null
D/PMS     (  906): releaseWL(43670238): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,I/GoogleHttpClient( 1223): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1223): Using GMS GoogleHttpClient
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1223/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1223/10028)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/CheckinRequestBuilder( 1223): awaiting user notification for token
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41b32bb0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 9 3 12
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4695 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4695): install
,I/MultiDex( 4695): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4695): loading existing secondary dex files
,I/MultiDex( 4695): load found 1 secondary dex files
,I/MultiDex( 4695): install done
,I/ProviderInstaller( 4695): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/jxcore-log( 4451): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4451): 
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4695/10028)
,I/Adreno-EGL( 4695): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4695): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4695): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4695): Local Branch: 
I/Adreno-EGL( 4695): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4695): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4695):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4695): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/PMS     (  906): releaseWL(4359a490): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 3905): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1843/10178)
D/PMS     (  906): acquireWL(44033fc0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1418/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4342/10100)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3905/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4553/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1884/1000)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/acms    ( 1884): Checking Certificates
I/acms    ( 1884): Checking Developer Certificates
I/acms    ( 1884): Checking Application Certificates
I/acms    ( 1884): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1884): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1884): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1884): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1884): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1884): Updating next query delay: 75600000
I/mlserverapp( 1884): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1884): cancelACMSProgrammedChecks
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3966/10051)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4342/10100)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,I/ConnectivityHelper( 1269): [onReceive] WIFI(1): CONNECTED
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1998/10021)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43becf30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  906): releaseWL(43becf30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  906): releaseWL(44033fc0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PMS     (  906): acquireWL(43734608): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1223 10028 null
D/PMS     (  906): releaseWL(43734608): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1365): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,W/fb4a(:<default>):UserScope( 4524): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4524): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
,D/PMS     (  906): acquireWL(43713dd0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1365 10028 null
D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1365): [NET] getaddrinfo-,err=8
D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1365): [NET] getaddrinfo-, 1
D/libc    ( 1365): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =f543 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/AutoSetting( 1404): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4553): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4553): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1404/10053)
,D/AutoSetting( 1404): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1404): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1404): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1404): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4584/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1404/10053)
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 234
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1365): [NET] getaddrinfo_proxy-, success
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4208/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4208/10160)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1843/10178)
,I/dalvikvm-heap( 4208): Grow heap (frag case) to 13.516MB for 1821008-byte allocation
,D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1365): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
,D/PMS     (  906): acquireWL(4366cd58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/PMS     (  906): releaseWL(4366cd58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/fb4a(:<default>):LocalFbBroadcastManager( 4524): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/PMS     (  906): acquireWL(41c29650): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/GCM     ( 1365): Connected
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/PMS     (  906): releaseWL(43713dd0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/PMS     (  906): releaseWL(41c29650): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(42daea88): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
,D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1365): Message class mpf
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
D/PMS     (  906): releaseWL(42daea88): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(424b7590): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,I/Adreno-EGL( 4695): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4695): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4695): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4695): Local Branch: 
I/Adreno-EGL( 4695): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4695): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4695):                  aa63bbd948f41d15fc72f585e
D/PMS     (  906): releaseWL(424b7590): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/Adreno-EGL( 4695): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4695): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4695): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4695): Local Branch: 
I/Adreno-EGL( 4695): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4695): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4695):                  aa63bbd948f41d15fc72f585e
,I/CheckinTask( 1223): Sending checkin request (8959 bytes)
,D/libc    ( 1223): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
D/libc    ( 1223): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6cb7 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 242
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1223): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
,D/PMS     (  906): releaseWL(42922950): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=10 [20][2][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42ec1a48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/PMS     (  906): releaseWL(42ec1a48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1223/10028)
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1223/10028)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [2][0][0]
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1223): awaiting user notification for token
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41dc6980 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 0 9 3 12
,I/CheckinTask( 1223): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1223): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/PMS     (  906): releaseWL(435e4d50): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 1223): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41dd6a50 that was originally bound here
E/ActivityThread( 1223): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41dd6a50 that was originally bound here
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
D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GCM     ( 1365): GCM config loaded
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =78a3 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/23.59.123.86
,D/AutoSetting( 1502): service - handleMessage() stop self
,D/AutoSetting( 1502): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=4342
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Killing 4342:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/AutoSetting( 1502): service - handleMessage() quit looper
,I/ActivityManager(  906): Recipient 4342
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV2    ( 4584): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  906): acquireWL(435b29d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1418 10028 null
,D/PMS     (  906): acquireWL(43f3dd58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1418 10028 null
,D/PMS     (  906): releaseWL(435b29d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): releaseWL(43f3dd58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/Process (  906): killProcessQuiet, pid=4365
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4365:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4365
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  906): acquireWL(4238f428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=123438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4238f428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(43b482e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b482e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42545ed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{421c1f60: PendingIntentRecord{424e0b30 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141057, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
,V/AlarmManager(  906): sending alarm PendingIntent{424eb078: PendingIntentRecord{423ca858 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141352, Int=0
,D/PMS     (  906): acquireWL(433d63c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/PMS     (  906): releaseWL(433d63c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(4405d5d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(42545ed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =8c83 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=243
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/AutoSetting( 1404): service - mHandler: update timezone
,D/AutoSetting( 1404): service - handleMessage() stop self
,D/AutoSetting( 1502): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1502): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1502): service - onCreate()
,D/AutoSetting( 1404): service - handleMessage() quit looper
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1404): service - onDestroy() END
D/AutoSetting( 1502): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1502): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1502): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1502): service - onStartCommand() handle command from HSP: processTimeZoneID
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
,D/AutoSetting( 1502): service - mHandler: update timezone
D/DotMatrix( 1567): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1502): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1502): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1502): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1502): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41ae39a0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 2 11 2 11
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(4405d5d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Process (  906): killProcessQuiet, pid=3966
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3966:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3966
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42649198 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42ad6210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42ad6210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/ContextImpl( 4657): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4233): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4233): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4233): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4233): Cust_ConnectToPC   : spcsc>false
D/        ( 4233): Cust_ConnectToPC   : IPT>true
,D/        ( 4233): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4233): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4233): Index of the first 1 = -1
W/ContextImpl( 4233): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
W/Settings( 4233): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4233): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4233): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4233): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4233): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 4233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1502): service - handleMessage() stop self
,D/AutoSetting( 1502): service - onDestroy() END
,D/AutoSetting( 1502): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4383
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  906): Killing 4383:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4383
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1242): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(43be02f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=183438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43be02f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42aefd40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42aefd40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43c3ecf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{43ba2020: PendingIntentRecord{4287ae08 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229795, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4744 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{424f2838: PendingIntentRecord{425884c0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450280857252, Int=10800000
,D/PMS     (  906): releaseWL(43c3ecf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026},
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4744/10047)
,D/Process (  906): killProcessQuiet, pid=4400
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4400:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4400
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(43073628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{436ccaa8: PendingIntentRecord{4345c900 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=230670, Int=120000
,V/AlarmManager(  906): sending alarm PendingIntent{42602d58: PendingIntentRecord{4287ae08 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=230786, Int=0
,D/PMS     (  906): releaseWL(43073628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(43baff08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=243438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43baff08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42dfab68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(42dfab68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(434d74b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(434d74b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42389e80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=303438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42389e80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43c38b48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(43c38b48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4451): Connected to the server!
I/jxcore-log( 4451): 
,I/chromium( 4451): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(43bbcaf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=363438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43bbcaf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1365): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1365): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1365): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1365): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1365): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1365): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1365): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1365): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41b18380 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4171): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4171): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4171): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4171): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4171): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4171): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4171): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4171): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1117): com.google.android.gms 2 16 4 12
,D/libc    ( 4171): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4171): [NET] getaddrinfo-,err=8
D/libc    ( 4171): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4171): [NET] getaddrinfo-, 1
,D/libc    ( 4171): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =bf3d +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4171): [NET] getaddrinfo_proxy-, success
I/global  ( 4171): call createSocket() return a new socket.
D/libc    ( 4171): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4171): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4171): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4171): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(42eb19e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(42eb19e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4360dce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=423438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4360dce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(440c38a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(440c38a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42ed7238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=483438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42ed7238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4317ebf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4317ebf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43f880e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=543438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43f880e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(436a9c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(436a9c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4408a308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=603439, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4408a308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43fd77a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43fd77a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1242): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1242): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1242): sku_id=99
,D/ContactMessageStore( 1242): start background delete task...
,D/ContactMessageStore( 1242): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1242): size: 0 , 0
,D/ContactMessageStore( 1242): Background delete complete
,D/PMS     (  906): acquireWL(43654548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{43ffc968: PendingIntentRecord{4345c900 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=530794, Int=300000
,V/AlarmManager(  906): sending alarm PendingIntent{4303b810: PendingIntentRecord{42351c20 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450281286378, Int=0
,D/PMS     (  906): releaseWL(43654548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4171): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4171): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4171): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4171): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4171): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/PMS     (  906): acquireWL(43c17800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=663438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43c17800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4282de58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10073}
,V/AlarmManager(  906): sending alarm PendingIntent{42ee2020: PendingIntentRecord{4462f258 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450281301584, Int=0
,D/PMS     (  906): releaseWL(4282de58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4171): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  906): acquireWL(4365bdb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4365bdb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Process (  906): killProcessQuiet, pid=4329
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4329:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4329
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(437de428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=723439, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(437de428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44354060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44354060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43bc02b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=783438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43bc02b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44049f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{41d6ebc0: PendingIntentRecord{423f9468 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785347, Int=0
,D/PMS     (  906): releaseWL(44049f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): acquireWL(4258d3a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4258d3a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(438ee378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,I/BatteryService(  906): n_update end
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(438ee378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43feb828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=843439, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43feb828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4341cd00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4341cd00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43f38338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=903438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43f38338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425e1068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425e1068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43577bf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=963438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43577bf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42cc16e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42cc16e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/ActivityManager(  906): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4777 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,D/PMS     (  906): acquireWL(43ba3448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10075}
,V/AlarmManager(  906): sending alarm PendingIntent{43f48128: PendingIntentRecord{44019e58 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
V/AlarmManager(  906): sending alarm PendingIntent{423ec530: PendingIntentRecord{423af018 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450281577588, Int=900000
,V/AlarmManager(  906): sending alarm PendingIntent{422013f0: PendingIntentRecord{43030a58 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450281647597, Int=0
,W/ContextImpl( 4657): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4657): call getInstance()
,D/SmartSyncUtils( 4657): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4657): MY_DEBUG = false
,D/PMS     (  906): acquireWL(4366c7d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4657 1000 null
,D/PMS     (  906): releaseWL(43ba3448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
D/SmartSyncScreenOnOffTimeReceiver( 4657): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4657): [updateNmRange] USERNIGHT_TIMESTART = 18, USERNIGHT_TIMEEND = 23, nStart = 18, nEnd = 23, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4657): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4657): SettingOnTime = 1450303200000, randomSettingOnTime = 1450302451000
,D/SmartSyncScreenOnOffTimeReceiver( 4657): SettingOffTime = 1450285200000, randomSettingOffTime = 1450290607000
D/SmartSyncScreenOnOffTimeReceiver( 4657): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4657): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4657): bNightModeTurnOffOnce = false
W/BatSI   (  906): Couldn't get kernel wake lock stats
D/PMS     (  906): releaseWL(4366c7d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ImageRamCache( 4777): create image Cache, size: 31457280.
I/ImageRamCache( 4777): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4777): create image Cache, size: 12582912.
,I/FeedSettings( 4777): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 4777): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4777): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4777): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4777): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4777): loadGridSize() with Alternative
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/libc    ( 4777): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4
D/libc    ( 4777): [NET] getaddrinfo-,err=8
D/libc    ( 4777): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 4777): [NET] getaddrinfo-, 1
,D/libc    ( 4777): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =e531 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=206
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4777): [NET] getaddrinfo_proxy-, success
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (4777/10075)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (4777/10075)
,D/Process (  906): killProcessQuiet, pid=4415
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4415:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4415
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(440911f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{4250fda0: PendingIntentRecord{424eadd8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1012406, Int=0
,D/PMS     (  906): acquireWL(44008330): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1365 10028 null
,D/PMS     (  906): releaseWL(44008330): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  906): releaseWL(440911f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): acquireWL(42e0a700): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/PMS     (  906): releaseWL(42e0a700): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): acquireWL(437f9f98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
,D/GCM     ( 1365): Message class mow
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
,D/PMS     (  906): acquireWL(41fe2b30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/PMS     (  906): releaseWL(437f9f98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): releaseWL(41fe2b30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=4 [368][16][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(43027710): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1023438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43027710): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44065b08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44065b08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(438273b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1083438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(438273b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42cfd0f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42cfd0f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/PMS     (  906): acquireWL(4303ad40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1143438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4303ad40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(424e0a88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424e0a88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425c84c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1203439, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425c84c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41ecfd00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41ecfd00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(425b8890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1263438, Int=0
,D/PMS     (  906): releaseWL(425b8890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43fcff90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43fcff90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4250d1b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1323438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4250d1b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4403a5b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4403a5b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42d68b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1383439, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42d68b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44089f28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44089f28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4358a108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1443438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4358a108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42545ea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42545ea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(436eeb70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(436eeb70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42ac8e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1503438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42ac8e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43be28b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43be28b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4394f1f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4394f1f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(440c1f30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1563439, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(440c1f30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43f51180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43f51180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4302fb90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4302fb90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42cf1b60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1623438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42cf1b60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4404a528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4404a528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43a88758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1683438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43a88758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43b06cd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b06cd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(435803e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1743438, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(435803e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43f88328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43f88328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(436f95a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1803439, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(436f95a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42445958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42445958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(43c31fc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d6ebc0: PendingIntentRecord{423f9468 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1505369, Int=0
D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{4232fbc8: PendingIntentRecord{424c3670 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820874, Int=1800000
D/PMS     (  906): acquireWL(43a51c60): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{43482d30: PendingIntentRecord{42331aa0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450282475825, Int=1800000
,V/AlarmManager(  906): sending alarm PendingIntent{423ec530: PendingIntentRecord{423af018 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450282477588, Int=900000
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,I/ProcessStatsService(  906): Prepared write state in 52ms
,D/PMS     (  906): releaseWL(43a51c60): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  906): acquireWL(44255fe8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1223 10028 null
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2015-12-16-02-32-34.bin
,D/PMS     (  906): acquireWL(4347cd98): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1223 10028 null
,D/PMS     (  906): releaseWL(44255fe8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,W/ContextImpl( 4657): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/EventLogService( 1223): Aggregate from 1450280747650 (log), 1450280675793 (data)
D/PMS     (  906): releaseWL(43c31fc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): releaseWL(4347cd98): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(44076a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bed1b8: PendingIntentRecord{41bec7e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1863439, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(44076a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(440659b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(440659b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43ff01a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{422d4e38: PendingIntentRecord{424eadd8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1912533, Int=0
,D/PMS     (  906): acquireWL(43fe7580): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1365 10028 null
,D/PMS     (  906): releaseWL(43fe7580): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/Process (  906): killProcessQuiet, pid=4208
I/ActivityManager(  906): Killing 4208:com.google.android.apps.plus/u0a160 (adj 15): empty for 1800s
,D/PMS     (  906): acquireWL(43fe7280): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/Process (  906): killProcessQuiet, pid=4584
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  906): killProcessQuiet, pid=4567
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  906): killProcessQuiet, pid=4553
D/PMS     (  906): releaseWL(43ff01a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
I/ActivityManager(  906): Killing 4584:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1800s
I/ActivityManager(  906): Killing 4567:com.android.chrome/u0a96 (adj 15): empty for 1800s
I/ActivityManager(  906): Killing 4553:com.google.android.setupwizard/u0a78 (adj 15): empty for 1800s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  906): killProcessQuiet, pid=3905
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  906): killProcessQuiet, pid=4500
I/ActivityManager(  906): Killing 3905:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
D/PMS     (  906): releaseWL(43fe7280): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/ActivityManager(  906): Killing 4500:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1807s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,I/ActivityManager(  906): Recipient 4553
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4208
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4567
,I/ActivityManager(  906): Recipient 4500
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3905
,D/MediaRouterService(  906): Client com.google.android.music (pid 3905): Died!
,D/GCM     ( 1365): Message class mow
,D/PMS     (  906): acquireWL(43c0f690): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10028)
,D/PMS     (  906): releaseWL(43c0f690): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): acquireWL(437a4758): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/PMS     (  906): releaseWL(437a4758): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/ActivityManager(  906): Recipient 4584
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,TIME-OUT KILL (timeout was 1800000ms),D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=4 [292][13][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/CustomizationManager( 4814): ====startRecUseTime====
D/htc.customization.log.level( 4814):  is 
W/CustomizationLogLevel( 4814): Level value is invalid, use default level 2
D/CustomizationManager( 4814):  Read ACC file spent 0.093 (s)
D/CIDMapFileReader( 4814): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4814): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4814): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4814): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4814): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4814): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4814): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4814): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4814): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4814): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4814): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4814): Parsing tag category name = system
I/CustomizationCIDLoader( 4814): Parsing tag category name = application
I/CustomizationCIDLoader( 4814): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4814): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4814): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4814): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4814): Parsing tag category name = Settings
D/CustomizationManager( 4814):  Read CID file spent 0.146 (s)
D/CustomizationManager( 4814):  All configurations done spent 0.148 (s)
W/HtcNativeFlag( 4814): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4814): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4814): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4814): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4814, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  906): killProcessQuiet, pid=4451
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  906): Killing 4451:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  906):   Force finishing activity ActivityRecord{42d33690 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  906): Copying FileAsset 0x62b88718 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  906): WIN DEATH: Window{42300ee8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  906): Client connection lost with reason: 4
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 4451 uid 10348
W/PackageSettings(  906): Skipping PackageSetting{421af548 com.example.hello/10356} due to missing metadata
W/Binder  ( 1210): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1210): java.lang.NullPointerException
W/Binder  ( 1210): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1210): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1210): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1210): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/acms    ( 1884): Unregistering com.test.thalitest
D/DotMatrix( 1567): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1567): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
E/acms    ( 1884): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1418): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): acquireWL(4295e818): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1418 10028 null
I/Prism.ItemManager( 4777): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4777): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  906): releaseWL(4295e818): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1302): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PackageBroadcastService( 1223): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/Launcher( 1269): Deferring update until onResume
D/Launcher( 1269): waitUntilResume // bindAppsRemoved
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4831 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
E/ExternalAccountType( 1331): Unsupported attribute readOnly
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
W/Parcel  ( 1255): Reading a NULL string not supported here.
I/MultiDex( 4831): install
E/cutils-trace( 4814): Error opening trace file: No such file or directory (2)
I/ActivityManager(  906): Delaying start of: ServiceRecord{436fec38 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/MultiDex( 4831): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4847 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/MultiDex( 4831): loading existing secondary dex files
I/MultiDex( 4831): load found 1 secondary dex files
I/MultiDex( 4831): install done
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PeopleContactsSync( 1223): CP2 sync disabled
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1223, uid=10028, userID:0
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4847): install
I/Icing   ( 1223): doRemovePackageData com.test.thalitest
D/PMS     (  906): acquireWL(43f0aab8): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
I/MultiDex( 4847): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
D/PMS     (  906): releaseWL(43f0aab8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4847): loading existing secondary dex files
I/MultiDex( 4847): load found 1 secondary dex files
I/MultiDex( 4847): install done
I/ProviderInstaller( 4831): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/ProviderInstaller( 4847): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1404): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1404): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1269): action: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2950): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4870 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteDBG( 2950): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63664fd0
W/dalvikvm( 2950): threadid=14: thread exiting with uncaught exception (group=0x4168fe30)
E/AndroidRuntime( 2950): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2950): Process: com.google.android.googlequicksearchbox:search, PID: 2950
E/AndroidRuntime( 2950): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 2950): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2950): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2950): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
E/AndroidRuntime( 2950): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/AndroidRuntime( 2950): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
E/AndroidRuntime( 2950): 	at cid.d(PG:192)
E/AndroidRuntime( 2950): 	at clo.g(PG:594)
E/AndroidRuntime( 2950): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2950): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2950): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2950): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2950): 	at clr.tL(PG:827)
E/AndroidRuntime( 2950): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2950): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2950): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2950): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2950): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2950): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2950): killProcess, pid=2950
D/Process ( 2950): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
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
E/SQLiteLog( 4831): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4831): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca008e8
E/DriveAsyncService( 4831): disk I/O error (code 3850)
E/DriveAsyncService( 4831): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4831): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4831): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4831): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4831): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4831): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4831): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4831): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4831): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4831): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4831): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4831): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4831): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4831): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4831): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 4831): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 4831): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca008e8
E/DocListDatabase( 4831): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4831): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4831): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4831): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4831): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4831): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4831): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4831): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4831): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4831): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4831): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4831): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4831): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4831): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4831): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4831): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4831): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4831): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4831): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4831): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4831): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4831): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4831): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4831): threadid=1: thread exiting with uncaught exception (group=0x4168fe30)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
D/Process ( 4831): killProcess, pid=4831
E/AndroidRuntime( 4831): FATAL EXCEPTION: main
E/AndroidRuntime( 4831): Process: com.google.android.gms.drive, PID: 4831
E/AndroidRuntime( 4831): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4831): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4831): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4831): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4831): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4831): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4831): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4831): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4831): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4831): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4831): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4831): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4831): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4831): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4831): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4831): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4831): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4831): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4831): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4831): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4831): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4831): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4831): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4831): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4831): 	... 10 more
D/Process ( 4831): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
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
I/ActivityManager(  906): Recipient 2950
I/ActivityManager(  906): Process com.google.android.googlequicksearchbox:search (pid 2950) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
D/MediaRouterService(  906): Client com.google.android.googlequicksearchbox (pid 2950): Died!
D/WifiService(  906): Client connection lost with reason: 4
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteDatabase( 4870): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4870): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4870): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4870): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4870): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4870): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4870): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4870): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4870): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4870): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4870): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4870): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4870): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4870): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4870): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4870): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4870): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4870): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4870): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4870): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4870): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4870): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4870): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4870): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4870): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4870): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4870): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4870): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4870): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4870): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4870): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4870): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4870): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4870): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4870): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4870): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4870): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4870): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4870): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4870): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4870): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4870): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4870): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4870): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4870): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4870): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4870): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4870): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4870): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4870): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4870): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4870): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4870): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4870): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4870): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4870): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4870): Opened ClientFlag.db in read-only mode
I/ActivityManager(  906): Recipient 4831
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4831) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 10918ms
E/SQLiteDatabase( 4870): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4870): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4870): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4870): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4870): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4870): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4870): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4870): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4870): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4870): threadid=11: thread exiting with uncaught exception (group=0x4168fe30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4870): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4870): Process: com.google.android.apps.docs, PID: 4870
E/AndroidRuntime( 4870): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4870): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4870): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4870): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4870): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4870): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4870): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4870): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4870): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4870): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4870): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4870): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4870): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4870): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4870): 	at aho.run(AbstractDatabaseInstance.java:455)
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
E/SQLiteDatabase( 4870): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4870): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4870): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4870): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4870): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4870): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4870): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4870): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4870): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4870): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4870): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4870): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4870): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4870): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4870): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4870): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4870): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4870): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4870): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4870): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4870): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4870): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4870): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4870): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4870): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4870): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4870): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4870): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4870): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4870): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4870): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4870): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4870): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4870): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4870): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4870): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4870): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4870): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 4870): killProcess, pid=4870
D/Process ( 4870): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
W/SQLiteOpenHelper( 4870): Opened ClientFlag.db in read-only mode
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4891 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4870
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4870) has died.
W/PackageManager(  906): Unable to load service info ResolveInfo{43fe2bb8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
W/ContextImpl( 4891): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4891): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
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
E/SQLiteDatabase( 4891): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4891): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4891): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4891): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4891): threadid=10: thread exiting with uncaught exception (group=0x4168fe30)
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4904 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 4891): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4891): Process: com.android.keychain, PID: 4891
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
E/AndroidRuntime( 4891): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4891): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4891): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4891): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  906): App crashed! Process: com.android.keychain
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
I/Prism.ItemManager( 4777): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4777): loadItems() com.htc.launcher.pageview.WidgetManager@41b297d8 +
I/Prism.WidgetManager( 4777): onLoadItems() +
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41b52f50 +
I/Prism.WidgetManager( 1269): onLoadItems() +
D/AppTag  ( 4904): getInstance(Context context)
D/Process ( 4891): killProcess, pid=4891
D/Process ( 4891): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/AppTag  ( 4904): getInstance(Context context)
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450282552068.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  906): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 4 more
D/AppTag  ( 4904): onCreate()
I/ActivityManager(  906): Recipient 4891
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.keychain (pid 4891) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20450ms
I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4919 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4939 uid=10098 gids={50098, 3003, 5012}

```
