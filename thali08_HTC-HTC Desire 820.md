#### Test 561510938d3c4f5_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/PMS     (  906): acquireWL(4241ca08): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
D/PMS     (  906): releaseWL(4241ca08): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  906): acquireWL(41c32320): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
D/PMS     (  906): releaseWL(41c32320): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  906): acquireWL(42526e80): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
D/PMS     (  906): releaseWL(42526e80): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  906): acquireWL(4224f018): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
D/PMS     (  906): releaseWL(4224f018): PARTIAL_WAKE_LOCK  Icing 0x1 null
,--------- beginning of /dev/log/main
E/cutils-trace( 4449): Error opening trace file: No such file or directory (2)
D/WIFI_ICON( 1115): WifiActivity: 0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/CustomizationManager( 4449): ====startRecUseTime====
D/htc.customization.log.level( 4449):  is 
W/CustomizationLogLevel( 4449): Level value is invalid, use default level 2
D/CustomizationManager( 4449):  Read ACC file spent 0.064 (s)
D/CIDMapFileReader( 4449): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4449): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4449): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4449): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4449): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4449): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4449): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4449): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4449): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4449): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4449): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4449): Parsing tag category name = system
I/CustomizationCIDLoader( 4449): Parsing tag category name = application
I/CustomizationCIDLoader( 4449): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4449): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4449): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4449): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4449): Parsing tag category name = Settings
D/CustomizationManager( 4449):  Read CID file spent 0.109 (s)
D/CustomizationManager( 4449):  All configurations done spent 0.110 (s)
W/HtcNativeFlag( 4449): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4449): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4449): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4449): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4449
D/PMS     (  906): acquireHCC(42e4a650): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(425b5ad8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x62ad4f58 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1122775648
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bab3e0
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
D/PMS     (  906): acquireWL(4244c7b0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4460 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1273): [trimMemory] 20
W/asset   ( 4460): Copying FileAsset 0x5c743428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4460): Binding Chromium to main looper Looper (main, tid 1) {41ac4370}
I/LibraryLoader( 4460): Expected native library version number "",actual native library version number ""
I/chromium( 4460): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4460): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(44193bc8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  906): acquireWL(441739c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43df1748:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4460): 1101898216: getState(). Returning 12
D/PMS     (  906): releaseWL(44193bc8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4460): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4460): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4460): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4460): Local Branch: 
I/Adreno-EGL( 4460): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4460): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4460):                  aa63bbd948f41d15fc72f585e
W/chromium( 4460): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4460): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4460): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4460): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4460): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4460): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4460): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4460): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4460): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4460): CordovaWebView is running on device made by: HTC
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1132): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,W/AwContents( 4460): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1273
,W/ResourceType( 4460): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4460): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b0b8d8, mServedView=org.apache.cordova.engine.SystemWebView{41ad1500 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/InputMethodManagerService(  906): Enable input method client, pid=4460
W/AwContents( 4460): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +294ms
,D/PMS     (  906): releaseWL(4244c7b0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4500 uid=10077 gids={50077}
D/PMS     (  906): acquireWL(4255ff30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
,V/AlarmManager(  906): sending alarm PendingIntent{424c9360: PendingIntentRecord{424b2e68 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452860442144, Int=60000
D/PMS     (  906): releaseWL(4255ff30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4500): SMSBackupAgentService started
,D/SMSBackup( 4500): Checking restore status
D/SMSBackup( 4500): Restore complete
,D/SMSBackup( 4500): cancelCheckAlarm
,D/SMSBackup( 4500): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3254
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3254:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3254
,D/JsMessageQueue( 4460): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4460): JniHelper::setJavaVM(0x4159a048), pthread_self() = 1663632656
,D/JX-Cordova( 4460): jxcore cordova android initializing
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 11.954MB for 42652-byte allocation
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 12.044MB for 95956-byte allocation
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 12.125MB for 143930-byte allocation
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 12.242MB for 215890-byte allocation
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 12.416MB for 323830-byte allocation
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 12.675MB for 485740-byte allocation
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 13.679MB for 1092904-byte allocation
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 14.590MB for 1639352-byte allocation
,D/PMS     (  906): acquireWL(4247c578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=80 rxSum=65} preTxRxSum={txSum=79 rxSum=64}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20218 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20219 delay=15s
V/AlarmManager(  906): sending alarm PendingIntent{423b94a8: PendingIntentRecord{42573e68 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105980, Int=0
D/PMS     (  906): releaseWL(4247c578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 15.902MB for 2459024-byte allocation
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
D/PMS     (  906): releaseHCC(42e4a650): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
,D/PMS     (  906): releaseHCC(425b5ad8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 18.024MB for 3688532-byte allocation
,W/jxcore-log( 4460): Initializing JXcore engine
,W/jxcore-log( 4460): JXcore engine is ready
,W/jxcore-log( 4460): Starting JXcore engine
,I/SensorManager(  906): mEventCount = 1350
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/jxcore-log( 4460): Platform android
W/jxcore-log( 4460): 
,W/jxcore-log( 4460): Process ARCH arm
W/jxcore-log( 4460): 
,D/PMS     (  906): releaseWL(441739c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1132): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:124, mTXpacketCount:123, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/jxcore-log( 4460): JXcore Cordova bridge is ready!
I/jxcore-log( 4460): 
,W/jxcore-log( 4460): JXcore engine is started
,I/chromium( 4460): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4460): Toggling radios to true
I/jxcore-log( 4460): 
,D/BluetoothAdapter( 4460): enable(): BT is already enabled..!
,D/WifiManager( 4460): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
,W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
,W/Settings:Agent(  906): Process.myPid(): 906
D/WifiService(  906): setWifiEnabled: true pid=4460, uid=10189
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
D/WifiService(  906): New client listening to asynchronous messages
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/Settings:Agent(  906): Process.myTid(): 1361
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
W/Settings:Agent(  906): << traceCallingStack(): 4(ms)
D/WifiManager( 4460): disconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
D/WifiManager( 4460): reconnect: Base Package Name=com.test.thalitest, uid=10189
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1132): TDLS: Tear down peers
I/wpa_supplicant( 1132): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4460): Radios toggled
I/jxcore-log( 4460): 
I/jxcore-log( 4460): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4460): 
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1132): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1132): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1132): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1132): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1132): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1132): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1132): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1132): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7a31bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1132):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1132): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1132): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1132): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1132): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1132): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1132): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1132): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1132): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1132): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1132): EAPOL: External notification - EA,P success=0
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1132): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1132): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1132): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1132): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1132): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1132): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1132): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1132): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1132): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1132): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1132): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1132): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1132): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1132): nl80211: Event message available
D/wpa_supplicant( 1132): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1132): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED,
,D/WifiNative-wlan0(  906):    returned true
,D/Tethering(  906): interfaceLinkStateChanged wlan0, false
,D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiPerfLock(  906): release()
,D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1132): Power_Mode_Type mode = 0
I/wpa_supplicant( 1132): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1132): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/WifiNative-wlan0(  906):    returned true
,D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  906): acquireWL(42585bc8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1132): Fast associate: Old scan results
I/wpa_supplicant( 1132): wpa_supplicant_scan enter
I/wpa_supplicant( 1132): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1132): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1132): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  906):    returned true
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 33
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
I/wpa_supplicant( 1132): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1132): nl80211: Event message available
D/wpa_supplicant( 1132): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20219 mDataStallAlarmIntent=PendingIntent{425cb410: PendingIntentRecord{42573e68 android broadcastIntent}}
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WIFI_ICON( 1115): WifiActivity: 0
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1132): Power_Mode_Type mode = 0
I/wpa_supplicant( 1132): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 61
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
,D/UsbnetStateTracker(  906): isAvailable+-
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1132): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WISPrService( 4191): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4191): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiService(  906): New client listening to asynchronous messages
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] entry_id:6   entry:0xb876f8e0  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb8773f48  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb8774818  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb87742d8  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb8774108  removed 
D/libc    (  363): [NET] entry_id:8   entry:0xb8773e48  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb87741d0  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8774410  removed 
D/libc    (  363): [NET] entry_id:9   entry:0xb8774010  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/PMS     (  906): acquireWL(442c66d8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10028 null
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(44199440): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): acquireWL(423da828): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WifiStateMachine(  906): Exit handleNetworkDisconnect
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/PMS     (  906): releaseWL(423da828): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
,D/WISPrService( 4191): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WISPrService( 4191): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1376/10028)
D/PMS     (  906): releaseWL(442c66d8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
D/PMS     (  906): releaseWL(44199440): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
,D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
,D/WifiNative-wlan0(  906): doBoolean: SCAN
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1132): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  906):    returned false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  906): bSetPropertyMultiRAB:false
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43c7f2e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43c7f2e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  906): NoActiveNetworkState
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 3880): type=WIFI subType= reason=null isConnected=false
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4344/10100)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3880/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1462/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1896/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4344/10100)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2465/10021)
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4527 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4527): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4527): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4527): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4527): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4527): Preparing secondary program dexes.
V/DexLibLoader( 4527): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4527): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4527): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
,V/DexLibLoader( 4527): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4527): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4527): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4527): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4527): Dex already copied
D/OdexVerifier( 4527): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4527): Creating class loader
,V/DexLibLoader( 4527): Finished creating class loader
V/DexLibLoader( 4527): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4527): Dex already copied
D/OdexVerifier( 4527): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4527): Creating class loader
,V/DexLibLoader( 4527): Finished creating class loader
V/DexLibLoader( 4527): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4527): Dex already copied
D/OdexVerifier( 4527): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4527): Creating class loader
,V/DexLibLoader( 4527): Finished creating class loader
V/DexLibLoader( 4527): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 4527): Dex already copied
D/OdexVerifier( 4527): Odex verification is skipped. OS version not supported.
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
D/wpa_supplicant( 1132): nl80211: Event message available
D/wpa_supplicant( 1132): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1132): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1132): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1132): nl80211: Survey data missing
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1132): Sorted scan results
I/wpa_supplicant( 1132): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1132): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1132): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1132): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-73
I/wpa_supplicant( 1132): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-86
D/wpa_supplicant( 1132): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1132): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1132): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1132): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1132): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1132): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1132): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1132): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1132): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1132): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1132): wpa_supplicant_pick_network+
I/wpa_supplicant( 1132): Selecting BSS from priority group 1
I/wpa_supplicant( 1132): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1132): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1132): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1132): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1132):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1132):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 1132): Start print parameters
I/wpa_supplicant( 1132): wpa_s->wpa_state is 3
I/wpa_supplicant( 1132): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1132): isConcurrentMode() is 0
I/wpa_supplicant( 1132): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1132): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1132): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1132): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1132): wpa_s->reassociate is 1
I/wpa_supplicant( 1132): wpa_s->is_screen_on 1
I/wpa_supplicant( 11,32): wpa_s->ifname wlan0
I/wpa_supplicant( 1132): End print parameters
I/wpa_supplicant( 1132): selected network = 1
D/wpa_supplicant( 1132): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7a334e8  current_ssid=0x0
D/wpa_supplicant( 1132): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1132): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1132): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1132): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1132): check if in concurrent case
,I/wpa_supplicant( 1132): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1132): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1132): wpa_supplicant_associate, 1780
,D/wpa_supplicant( 1132): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1132): RSN: PMKSA cache search - network_ctx=0xb7a334e8 try_opportunistic=0
D/wpa_supplicant( 1132): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1132): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1132): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1132): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1132): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1132): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1132): nl80211: Unsubscribe mgmt frames handle 0xb7a32718 (mode change)
D/wpa_supplicant( 1132): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7a32718
D/wpa_supplicant( 1132): nl80211: Register frame type=0xd0 nl_handle=0xb7a32718
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1132): nl80211: Register frame type=0xd0 nl_handle=0xb7a32718
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1132): nl80211: Register frame type=0xd0 nl_handle=0xb7a32718
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1132): nl80211: Register frame type=0xd0 nl_handle=0xb7a32718
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1132): nl80211: Register frame type=0xd0 nl_handle=0xb7a32718
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1132): nl80211: Register frame type=0xd0 nl_handle=0xb7a32718
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1132): nl80211: Register frame type=0xd0 nl_handle=0xb7a32718
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1132): nl80211: Register frame type=0xd0 nl_handle=0xb7a32718
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1132): nl80211: Register frame type=0xd0 nl_handle=0xb7a32718
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1132): nl80211: Register frame type=0xd0 nl_handle=0xb7a32718
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1132): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1132):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1132):   * freq=2412
D/wpa_supplicant( 1132):   * Auth Type 0
D/wpa_supplicant( 1132):   * WPA Versions 0x2
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1132): nl80211: Connect request send successfully
D/wpa_supplicant( 1132): EAPOL: External notification - EAP success=0,
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1132): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1132): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=,
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1132): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1132): WPS: Unknown Vendor Extension (Vendor ID 311),
I/wpa_supplicant( 1132): reply (634) for get BSS: id=0
I/wpa_supplicant( 1132): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1132): freq=5220
I/wpa_supplicant( 1132): level=-48
I/wpa_supplicant( 1132): tsf=0000000110001298
I/wpa_supplicant( 1132): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1132): ssid=NG7005g
I/wpa_supplicant( 1132): ====
I/wpa_supplicant( 1132): id=1
I/wpa_supplicant( 1132): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1132): freq=2412
I/wpa_supplicant( 1132): level=-50
I/wpa_supplicant( 1132): tsf=0000000110001319
I/wpa_supplicant( 1132): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1132): ssid=NG700
I/wpa_supplicant( 1132): ====
I/wpa_supplicant( 1132): id=2
I/wpa_supplicant( 1132): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1132): freq=2452
I/wpa_supplicant( 1132): level=-73
I/wpa_supplicant( 1132): tsf=0000000110001323
I/wpa_supplicant( 1132): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1132): ssid=Gonzos
I/wpa_supplicant( 1132): ====
I/wpa_supplicant( 1132): id=3
I/wpa_supplicant( 1132): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1132): freq=2412
I/wpa_supplicant( 1132): level=-50
I/wpa_supplicant( 1132): tsf=0000000110001312
I/wpa_supplicant( 1132): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1132): ssid=01ABC
I/wpa_supplicant( 1132): ====
I/wpa_supplicant( 1132): id=4
I/wpa_supplicant( 1132): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1132): freq=2437
I/wpa_supplicant( 1132): level=-86
I/wpa_supplicant( 1132): tsf=0000000110001327
I/wpa_supplicant( 1132): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1132): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1132): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 110001298, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 110001319, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2452, timestamp: 110001323, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 110001312, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -86, frequency: 2437, timestamp: 110001327, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,E/FbInjectorInitializer( 4527): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1132): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1132): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1132): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1132): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1132): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1132): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1132): nl80211: if_removed already cleared - ignore event
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1132): nl80211: Event message available
D/wpa_supplicant( 1132): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1132): nl80211: Connect event
D/wpa_supplicant( 1132): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1132): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1132): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1132): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1132): netlink: Operstate: linkmode=-1, operstate=5
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1132): Add randomness: count=11 entropy=5
I/wpa_supplicant( 1132): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1132): TDLS: Remove peers on association
D/wpa_supplicant( 1132): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1132): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1132): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1132): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1132): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1132): EAPOL: enable timer tick
D/wpa_supplicant( 1132): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1132): htc_wext_set_keepalive +
I/wpa_supplicant( 1132): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1132): getPrivFuncNum +	
I/wpa_supplicant( 1132): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1132): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1132): htc_wext_set_keepalive - ret = 0
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 1132): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/wpa_supplicant( 1132): Get randomness: len=32 entropy=6
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false,
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Associated
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 1132): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7a329f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1132):    addr=c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 11
D/WifiStateMachine(  906): This record is existed, only update it...
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1132): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1132): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f8bb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1132):    broadcast key
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1132): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1132): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1132): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1132): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/wpa_supplicant( 1132): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1132): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1132): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1132): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1132): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1132): set send_ind_to_ndc = 0
I/wpa_supplicant( 1132): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1132): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1132): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1132): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1132): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1132): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1132): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1132): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1132): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1132): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1132): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1132): EAPOL authentication completed successfully
I/wpa_supplicant( 1132): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1132): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1132): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1132): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WISPrService( 4191): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4191): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/DhcpStateMachine(  906): [StoppedState] Start DHCP
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1132): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1132): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1132): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1132): Power_Mode_Type mode = 1
I/wpa_supplicant( 1132): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1132): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1132): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(43e3d240): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  906):    returned null
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41b086a0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41b086a0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4527): Verify
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4527): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4527): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 9.511MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=4259
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4259:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/PMS     (  906): acquireWL(42377a28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
,D/PMS     (  906): acquireWL(42c2c818): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1226 10028 null
,D/PMS     (  906): releaseWL(42377a28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,I/ActivityManager(  906): Recipient 4259
,D/GCM     ( 1376): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/PMS     (  906): releaseWL(42c2c818): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1414): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4556 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1414/10053)
,D/AutoSetting( 1414): Util - no network available!
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1414/10053)
,D/AutoSetting( 1414): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1414): service - mHandler: cancel location update
,D/AutoSetting( 1414): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4527): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4527): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4527): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4556): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4556): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4556): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4556): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/Process (  906): killProcessQuiet, pid=4281
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4570 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 4281:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4556/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4556/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4556/10078)
,I/ActivityManager(  906): Recipient 4281
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4527): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/Process (  906): killProcessQuiet, pid=3863
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4587 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Killing 3863:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 9.959MB for 84664-byte allocation
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4587): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 9.974MB for 28144-byte allocation
,W/ContextImpl( 4587): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,E/dalvikvm( 4527): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4527): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
E/dalvikvm( 4527): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4527): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4527): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4527): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4527): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4527): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4527): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4527): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4527): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4527): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4527): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/GAV2    ( 4587): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/dalvikvm( 4527): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4527): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4527): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4527): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4527): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4587): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4587): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 10.042MB for 39954-byte allocation
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1132): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1132): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1132): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 10.119MB for 79892-byte allocation
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  906): releaseWL(43e3d240): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,I/ActivityManager(  906): Recipient 3863
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1132): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1132): WiFi gateway: 0x101a8c0
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20221 delay=15s
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  906): WAN detection
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
,D/WISPrService( 4191): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4587/10151)
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@42360888
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
V/WebViewChromiumFactoryProvider( 4587): Binding Chromium to main looper Looper (main, tid 1) {41ac93b8}
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
,I/LibraryLoader( 4587): Expected native library version number "",actual native library version number ""
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/chromium( 4587): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4587): Initializing chromium process, renderers=0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,E/AudioManagerAndroid( 4587): BLUETOOTH permission is missing!
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/PMS     (  906): acquireWL(43887778): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  906): acquireWL(43d31d70): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  906): releaseWL(43887778): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,I/QuickSettingWifi( 1115): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(43320770): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4556/10078)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1132): environment dirty rate=0 [1][0][0]
,I/Adreno-EGL( 4587): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4587): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4587): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4587): Local Branch: 
I/Adreno-EGL( 4587): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4587): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4587):                  aa63bbd948f41d15fc72f585e
D/PMS     (  906): acquireWL(43d32a10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
,D/PMS     (  906): acquireWL(43e3dfd0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1226 10028 null
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
D/PMS     (  906): releaseWL(43d32a10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,I/CheckinService( 1226): Preparing to send checkin request
,I/EventLogService( 1226): Accumulating logs since 1452860393986
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 10.281MB for 75760-byte allocation
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/NSApplication( 4587): Starting up...
,I/GoogleHttpClient( 1226): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1226): Using GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{437863a0 u0 ReceiverList{437862a0 4527 com.facebook.katana/10026/u0 remote:435a9ca0}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{437863a0 u0 ReceiverList{437862a0 4527 com.facebook.katana/10026/u0 remote:435a9ca0}}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4587/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4587/10151)
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{423317a8 u0 ReceiverList{42331658 4527 com.facebook.katana/10026/u0 remote:4420f478}}
D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/PMS     (  906): releaseWL(43320770): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4169/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4169/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
,D/Process (  906): killProcessQuiet, pid=4314
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42123750
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42123750, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423427a8
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@425e0760
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  906): Killing 4314:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/PMS     (  906): Going to sleep due to screen timeout...
W/BatSI   (  906): Couldn't get kernel wake lock stats
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,I/ActivityManager(  906): Recipient 4314
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
,W/PMS     (  906): mWirelessDisplayManager is null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1226/10028)
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1226/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
,D/GCM     ( 1376): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): acquireWL(42e31f70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1462 10028 null
D/PMS     (  906): releaseWL(42e31f70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
,D/GCoreFlp( 1462): Unknown pending intent to remove.
D/PMS     (  906): acquireWL(43d6e5c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1462 10028 null
D/PMS     (  906): releaseWL(43d6e5c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/GLSUser ( 1376): GoogleAccountDataService.getToken()
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1376): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/wpa_supplicant( 1132): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1132): EAPOL: disable timer tick
,W/CheckinRequestBuilder( 1226): awaiting user notification for token
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,D/DotMatrix( 1570): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41b32be8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 6 3 12
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 385ms
D/NfcService( 1256): ScreenObserver: OFF
,D/NfcService( 1256): applyRouting - 0
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
I/InputMethodManagerService(  906): Disable input method client, pid=4460
I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43691360)
D/PMN     (  906): wakingUp
,D/NfcService( 1256): applyRouting -2
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  906): acquireWL(43981088): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  906): releaseWL(43981088): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  906): No lock screen! windowToken=null
D/PMN     (  906): onScreenOn
,D/MtpService( 2465): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2465): [MTP][onReceive]-
,D/NfcService( 1256): applyRouting - 0
,D/NfcService( 1256): applyRouting -2
D/PMS     (  906): acquireWL(43dff730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(43dff730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): acquireWL(42a5da08): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  906): releaseWL(42a5da08): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/AutoSetting( 1414): receiver - intent: android.intent.action.USER_PRESENT
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/TetherSettings( 4191): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4191): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4191): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4191): Cust_ConnectToPC   : spcsc>false
D/        ( 4191): Cust_ConnectToPC   : IPT>true
D/        ( 4191): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4191): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4191): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4191): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4191): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/AutoSetting( 1414): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 4191): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 4191): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4191): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4191):  defaultType:0
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
W/ContextImpl( 4191): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
I/ClockThread( 1115): stop update clock
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20222 delay=15s
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1132): SET_SCREEN_ON:On
I/wpa_supplicant( 1132): htc_wext_set_keepalive +
I/wpa_supplicant( 1132): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1132): getPrivFuncNum +	
I/wpa_supplicant( 1132): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1132): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1132): htc_wext_set_keepalive - ret = 0
,I/wpa_supplicant( 1132): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1132): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true,
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1115): WifiActivity: 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1132): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  906): BroadcastRSSIForIMS, newrssi =-50 , oldRssi= -200
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4675 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1132): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4527): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4527): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/Choreographer( 4460): Skipped 242 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4460): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4460): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41ad1500 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 4460): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4687 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/PMS     (  906): releaseWL(42585bc8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,I/NetworkMonitor( 3880): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3880/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1462/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4556/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4344/10100)
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0],
V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/ConnectivityHelper( 1273): [onReceive] WIFI(1): CONNECTED
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
I/acms    ( 1896): Checking Certificates
I/acms    ( 1896): Checking Developer Certificates
I/acms    ( 1896): Checking Application Certificates,
I/acms    ( 1896): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1896): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1896): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1896): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1896): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1896): Updating next query delay: 75600000
,I/mlserverapp( 1896): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1896): cancelACMSProgrammedChecks
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
I/MultiDex( 4687): install
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1896/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10075)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/MultiDex( 4687): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  906): NoActiveNetworkState
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
,I/MultiDex( 4687): loading existing secondary dex files
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3936/10051)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4344/10100)
W/ContextImpl( 4675): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/PMS     (  906): acquireWL(43dfba58): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
I/MultiDex( 4687): load found 1 secondary dex files
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,I/MultiDex( 4687): install done
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1462/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(431afa50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
I/ProviderInstaller( 4687): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(43dbe728): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4675 1000 null
,D/NetworkPolicy(  906): updateScreenOn: false
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/SmartSyncUtils( 4675): isEpsOn(), nState = 0
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(42e26c08): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
,I/ActivityManager(  906): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4709 uid=10106 gids={50106, 3003, 5012}
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  906): releaseWL(431afa50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  906): releaseWL(43dfba58): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PMS     (  906): releaseWL(43dbe728): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,E/ExternalAccountType( 1327): Unsupported attribute readOnly
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/SmartSyncUtils( 4675): getMobilePolicyEnabled, result = true
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1795): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1795): onScreenOn: 1452860449721
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1795): onScreenOn: 1452860449721
D/PMS     (  906): acquireWL(43ba0128): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1462 10028 null
D/PMS     (  906): releaseWL(43ba0128): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/Process (  906): killProcessQuiet, pid=4344
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4344:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423427a8
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423427a8, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@425e0760
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
,I/ActivityManager(  906): Recipient 4344
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/PMS     (  906): acquireWL(4355d098): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2465/10021)
,D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20222 mDataStallAlarmIntent=PendingIntent{43d7ca88: PendingIntentRecord{42573e68 android broadcastIntent}}
D/PMS     (  906): releaseWL(4355d098): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1132): SET_SCREEN_ON:Off
I/wpa_supplicant( 1132): htc_wext_set_keepalive +
I/wpa_supplicant( 1132): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1132): getPrivFuncNum +	
I/wpa_supplicant( 1132): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1132): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1132): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1132): htc_wext_set_keepalive gateway addr = c0a80101
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
,I/wpa_supplicant( 1132): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  906):    returned true
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(431c2120): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
,V/SRS_Proc(  370): ParamSet string: screen_state=off
,D/NetworkPolicy(  906): updateScreenOn: false
,D/wpa_supplicant( 1132): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/ContactMessageStore( 1240): start background delete task...
D/ContactMessageStore( 1240): size: 0 , 0
,D/ContactMessageStore( 1240): Background delete complete
D/PMS     (  906): acquireWL(42a7eba8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
,D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): releaseWL(431c2120): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42a7eba8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [1][0][0]
,D/GCM     ( 1376): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
D/AutoSetting( 1414): service - mHandler: cancel location update
,D/AutoSetting( 1414): service -           changes count: 0
,D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] getTotalRam: 1873 Mb
D/libc    ( 1376): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1376): [NET] getaddrinfo-,err=8
D/libc    ( 1376): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1376): [NET] getaddrinfo-, 1
,D/libc    ( 1376): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/libc    (  363): [NET] +++++ res_nsend xid =c79c +++++
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
,D/PMS     (  906): acquireWL(441c23c0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1376 10028 null
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1795): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1795): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1795): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1795): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1795): onScreenOff
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
D/PMS     (  906): acquireWL(4419f588): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1462 10028 null
D/PMS     (  906): releaseWL(4419f588): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/AutoSetting( 1414): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4556): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4556): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1414): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1414): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1414/10053)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1414/10053)
D/AutoSetting( 1414): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1414): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4587/10151)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4169/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4169/10160)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1376): [NET] getaddrinfo_proxy-, success
,D/GCM     ( 1376): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
I/dalvikvm-heap( 4169): Grow heap (frag case) to 13.500MB for 1821008-byte allocation
,W/ContextImpl( 4675): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4675): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4675): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4675): isEpsOn(), nState = 0
D/WifiService(  906): New client listening to asynchronous messages
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425e0760
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425e0760, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425e0760, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425e0760
,E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425e4410 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425e4410 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/libc    ( 1376): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1376): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
D/PMS     (  906): acquireWL(43d9f120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
D/PMS     (  906): releaseWL(43d9f120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/NewsWeather( 4709): LocationClient connecting
,I/NewsWeather( 4709): NewsAccounts: 2, AllSystemAccounts 1.
,E/dalvikvm( 4709): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
E/ProviderInstaller( 4709): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,I/Adreno-EGL( 4687): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4687): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4687): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4687): Local Branch: 
I/Adreno-EGL( 4687): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4687): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4687):                  aa63bbd948f41d15fc72f585e
E/dalvikvm( 4709): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4709): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4709): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/Adreno-EGL( 4687): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4687): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4687): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4687): Local Branch: 
I/Adreno-EGL( 4687): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4687): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4687):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  906): acquireWL(43d5f728): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10028 null
,D/GCM     ( 1376): Connected
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
D/PMS     (  906): releaseWL(441c23c0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1376/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
D/PMS     (  906): releaseWL(43d5f728): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(43cf3a70): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
,I/ProviderInstaller( 4709): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1376): Message class mpf
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1376/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1376/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43c42038): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(43c42038): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4709): Last usage 0, idle 1452860450s, sync interval 2592000s
,I/NewsWeather( 4709): setPeriodicSync in seconds 2592000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4687/10028)
,I/NewsWeather( 4709): onConnected null
D/PMS     (  906): acquireWL(4362b7c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
D/PMS     (  906): releaseWL(43cf3a70): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(42e2a650): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1462 10028 null
D/PMS     (  906): releaseWL(4362b7c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): acquireWL(429a0e40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1462 10028 null
W/GCoreFlp( 1462): No location to return for getLastLocation()
I/NewsWeather( 4709): LocationClient onConnected: location null
,I/NewsWeather( 4709): Skip sync for lookup editions
,I/NewsWeather( 4709): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4709): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,D/PMS     (  906): releaseWL(42e2a650): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): releaseWL(429a0e40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/GLSUser ( 1376): GoogleAccountDataService.getToken()
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1376): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1570): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/NewsWeather( 4709): Unrecoverable authentication exception
E/NewsWeather( 4709): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4709): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4709): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4709): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41c159d0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 2 10 2 12
,D/libc    ( 4709): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4709): [NET] getaddrinfo-,err=8
D/libc    ( 4709): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4709): [NET] getaddrinfo-, 1
,D/libc    ( 4709): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =3d19 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 216
D/libc    (  363): [NET]res_nsend:resplen=70
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4709): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4709): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4709): [NET] getaddrinfo-,err=8
,E/NewsWeather( 4709): Failed to syncNewsAppData
,E/NewsWeather( 4709): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  906): acquireWL(42394660): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
D/PMS     (  906): releaseWL(42394660): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43cc18b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 68976, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  906): releaseWL(42e26c08): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/Process (  906): killProcessQuiet, pid=4367
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Killing 4367:com.htc.backup/1000 (adj 15): empty #17
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=6 [16][1][0]
,W/Settings( 4687): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(43cc18b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1462/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(423e8730): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  906): releaseWL(423e8730): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  906): Recipient 4367
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/ExternalAccountType( 1327): Unsupported attribute readOnly
,I/Adreno-EGL( 4687): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4687): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4687): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4687): Local Branch: 
I/Adreno-EGL( 4687): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4687): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4687):                  aa63bbd948f41d15fc72f585e
,I/CheckinTask( 1226): Sending checkin request (9009 bytes)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1226): [NET] getaddrinfo-, 1
D/libc    ( 1226): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =190a +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 222
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
W/fb4a(:<default>):UserScope( 4527): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1226): [NET] getaddrinfo_proxy-, success
,W/fb4a(:<default>):UserScope( 4527): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC <<
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1132): environment dirty rate=25 [4][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1132): environment dirty rate=0 [1][0][0]
,D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4527): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4527/10026)
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =3c1b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/PMS     (  906): acquireWL(42520f40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
,D/PMS     (  906): releaseWL(42520f40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): releaseWL(43d31d70): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1226/10028)
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1226/10028)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1132): environment dirty rate=35 [14][5][0]
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/104.81.130.175
,W/GLSUser ( 1376): GoogleAccountDataService.getToken()
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1376): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1570): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1115): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1226): awaiting user notification for token
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e495e0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 8 3 12
,I/CheckinTask( 1226): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1226): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/GCM     ( 1376): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): releaseWL(43e3dfd0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1226): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41ba1c08 that was originally bound here
E/ActivityThread( 1226): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41ba1c08 that was originally bound here
E/ActivityThread( 1226): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1226): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1226): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1226): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1226): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1226): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1226): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1226): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1226): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1226): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1226): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1226): 	at bks.a(SourceFile:298)
E/ActivityThread( 1226): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1226): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1226): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1226): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1376): GCM config loaded
,I/GAV2    ( 4587): Thread[GAThread,5,main]: No campaign data found.
,D/AutoSetting( 1511): service - handleMessage() stop self
,D/AutoSetting( 1511): service - onDestroy() END
,D/AutoSetting( 1511): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4331
,I/ActivityManager(  906): Killing 4331:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4331
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV4    ( 4709): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  906): killProcessQuiet, pid=4386
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4386:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4386
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  906): acquireWL(425bf5c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=122348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425bf5c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(4419e910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4419e910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4248ce68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c7f9f8: PendingIntentRecord{42462c50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=133787, Int=0
,D/PMS     (  906): acquireWL(42574490): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/PMS     (  906): releaseWL(4248ce68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43df81a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42574490): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(43df81a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42c615e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423eb320: PendingIntentRecord{423ec0b0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141785, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42e460c0: PendingIntentRecord{425052b8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142229, Int=0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(43df01f8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42c615e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
D/AutoSetting( 1414): service - handleMessage() stop self
,D/AutoSetting( 1414): service - mHandler: update timezone
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =e225 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  906): acquireWL(43280718): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
D/PMS     (  906): releaseWL(43280718): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1511): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1511): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1511): service - onCreate()
D/AutoSetting( 1511): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1511): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1414): service - handleMessage() quit looper
,D/AutoSetting( 1414): service - onDestroy() END
D/DotMatrix( 1570): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1511): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1511): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1511): service - mHandler: update timezone
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 2
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/AutoSetting( 1511): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1511): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1511): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1511): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1570): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/PhoneStatusBar( 1115): removeNotification.gc:51
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e7d940 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 3 5 2 11
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(43df01f8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Process (  906): killProcessQuiet, pid=3936
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3936:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3936
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42acf970 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  906): acquireWL(446e66d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(446e66d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425f59a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c7f9f8: PendingIntentRecord{42462c50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=163806, Int=0
,D/PMS     (  906): acquireWL(4331c758): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/PMS     (  906): releaseWL(425f59a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43c3c8a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=22 [40][9][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(425dcec8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(4331c758): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(43c3c8a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42e145e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,I/NewsWeather( 4709): Last usage 0, idle 1452860501s, sync interval 2592000s
,I/NewsWeather( 4709): setPeriodicSync in seconds 2592000
D/PMS     (  906): releaseWL(42e145e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4709): Skip sync for lookup editions
,I/NewsWeather( 4709): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4709): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1376): GoogleAccountDataService.getToken()
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1376): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1570): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 4709): Unrecoverable authentication exception
E/NewsWeather( 4709): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4709): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4709): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4709): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41ec7a50 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 11 4 12
,D/PMS     (  906): acquireWL(441c42f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
,E/NewsWeather( 4709): Failed to syncNewsAppData
,E/NewsWeather( 4709): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  906): releaseWL(441c42f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43d2bba8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 112992, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  906): releaseWL(425dcec8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): releaseWL(43d2bba8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(4234a070): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1462/10028)
,D/PMS     (  906): releaseWL(4234a070): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1327): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1511): service - handleMessage() stop self
,D/AutoSetting( 1511): service - onDestroy() END
,D/AutoSetting( 1511): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4402
,I/ActivityManager(  906): Killing 4402:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4402
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1240): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(425baca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=182348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425baca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(431a7170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(431a7170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43bf7200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c7f9f8: PendingIntentRecord{42462c50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=193865, Int=0
,D/PMS     (  906): acquireWL(441e04a0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): releaseWL(43bf7200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(437940b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(441e04a0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(437940b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(441c1890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c7f9f8: PendingIntentRecord{42462c50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=227542, Int=0
,D/PMS     (  906): acquireWL(42e46330): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): releaseWL(441c1890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43865d70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=42 [7][3][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0,
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(441b96f0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
,D/PMS     (  906): releaseWL(42e46330): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(43865d70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43979878): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43979878): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4709): Last usage 0, idle 1452860565s, sync interval 2592000s
,I/NewsWeather( 4709): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4709): Skip sync for lookup editions
,I/NewsWeather( 4709): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4709): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1376): GoogleAccountDataService.getToken()
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1376): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1570): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 4709): Unrecoverable authentication exception
E/NewsWeather( 4709): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4709): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4709): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4709): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41bf0a58 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 9 3 12
,E/NewsWeather( 4709): Failed to syncNewsAppData
,E/NewsWeather( 4709): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  906): acquireWL(43887ae0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
D/PMS     (  906): releaseWL(43887ae0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(423c1dc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 164218, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  906): releaseWL(441b96f0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1462/10028)
D/PMS     (  906): releaseWL(423c1dc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42c679d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42c679d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1327): Unsupported attribute readOnly
,D/PMS     (  906): acquireWL(42560a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{41f51368: PendingIntentRecord{42c23738 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231640, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4773 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{42516940: PendingIntentRecord{4251a898 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452860558774, Int=10800000
,D/PMS     (  906): releaseWL(42560a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4773/10047)
,D/Process (  906): killProcessQuiet, pid=4417
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4417:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4417
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/PMS     (  906): acquireWL(42c68d50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{441b0990: PendingIntentRecord{4414b948 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=231645, Int=120000
,V/AlarmManager(  906): sending alarm PendingIntent{42beb0f8: PendingIntentRecord{42c23738 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=232104, Int=0
,D/PMS     (  906): releaseWL(42c68d50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(43be5080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=242348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43be5080): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(438457a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(438457a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43e3ef60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c7f9f8: PendingIntentRecord{42462c50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=257617, Int=0
,D/PMS     (  906): acquireWL(43483870): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43e3ef60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43184c40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43483870): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(43184c40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(43be4500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43be4500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  906): acquireWL(4358c3d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=302347, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4358c3d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(425dd868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425dd868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(42c54118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c7f9f8: PendingIntentRecord{42462c50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=354722, Int=0
,D/PMS     (  906): acquireWL(43bf9140): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/PMS     (  906): releaseWL(42c54118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(425b4ac0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=30 [30][9][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(433fce90): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
D/PMS     (  906): releaseWL(43bf9140): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(425b4ac0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43dcd298): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,I/NewsWeather( 4709): Last usage 0, idle 1452860692s, sync interval 2592000s
,I/NewsWeather( 4709): setPeriodicSync in seconds 2592000
,D/PMS     (  906): releaseWL(43dcd298): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4709): Skip sync for lookup editions
,I/NewsWeather( 4709): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4709): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1376): GoogleAccountDataService.getToken()
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1376): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1570): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/NewsWeather( 4709): Unrecoverable authentication exception
E/NewsWeather( 4709): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4709): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4709): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4709): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41b0cc08 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 9 4 12
,D/PMS     (  906): acquireWL(43dfb0c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
,D/PMS     (  906): releaseWL(43dfb0c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4709): Failed to syncNewsAppData
,E/NewsWeather( 4709): Down sync of news app Failed, error code: SYNC_IO_ERROR
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43ded8f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 228075, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/PMS     (  906): releaseWL(433fce90): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/PMS     (  906): releaseWL(43ded8f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1462/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/PMS     (  906): acquireWL(438464c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(438464c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1327): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4327e580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=362348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4327e580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1376): GoogleAccountDataService.getToken()
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1376): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1570): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1376): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1376): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1376): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1376): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1376): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1376): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1376): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1376): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,E/PlayEventLogger( 4134): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4134): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4134): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4134): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4134): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4134): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4134): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4134): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e759d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 2 11 4 12
,D/libc    ( 4134): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4134): [NET] getaddrinfo-,err=8
D/libc    ( 4134): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4134): [NET] getaddrinfo-, 1
,D/libc    ( 4134): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =ddd8 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4134): [NET] getaddrinfo_proxy-, success
I/global  ( 4134): call createSocket() return a new socket.
D/libc    ( 4134): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4134): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4134): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4134): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(42c1ef40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42c1ef40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(42be0310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/PMS     (  906): acquireWL(42bcf858): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{41c7f9f8: PendingIntentRecord{42462c50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=384765, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): releaseWL(42be0310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42a68ea0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42bcf858): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(42a68ea0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42568180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=422347, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42568180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42561830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42561830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42554ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=482348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42554ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4254bc68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4254bc68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42545898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PowerUI ( 1115): closing low battery warning: level=100
,D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(42545898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42492ec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=542347, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42492ec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4236d568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4236d568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42049b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=602348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42049b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(424ab018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/PMS     (  906): acquireWL(4249c4e8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{41c7f9f8: PendingIntentRecord{42462c50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=608350, Int=0
D/PMS     (  906): releaseWL(424ab018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(423bc798): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=17 [35][6][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(433f6d38): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(4249c4e8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(423bc798): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4251b2f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4251b2f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4709): Last usage 0, idle 1452860946s, sync interval 2592000s
,I/NewsWeather( 4709): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4709): Skip sync for lookup editions
,I/NewsWeather( 4709): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4709): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1376): GoogleAccountDataService.getToken()
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1376): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1570): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,E/NewsWeather( 4709): Unrecoverable authentication exception
E/NewsWeather( 4709): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4709): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4709): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4709): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41d84398 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 4709): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4709): [NET] getaddrinfo-,err=8
D/libc    ( 4709): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4709): [NET] getaddrinfo-, 1
,D/libc    ( 4709): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =9303 +++++
,D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
I/RemoteViews.Performance( 1115): com.google.android.gms 4 10 4 12
,D/libc    ( 4709): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4709): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4709): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(423500a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
,E/NewsWeather( 4709): Failed to syncNewsAppData
,D/PMS     (  906): releaseWL(423500a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/NewsWeather( 4709): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(436a8708): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 355055, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  906): releaseWL(433f6d38): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PMS     (  906): releaseWL(436a8708): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1462/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4300a538): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4300a538): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1327): Unsupported attribute readOnly
,D/PMS     (  906): acquireWL(423fcc78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(423fcc78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(436a8938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{425b5af8: PendingIntentRecord{4414b948 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=532115, Int=300000
,V/AlarmManager(  906): sending alarm PendingIntent{43736c98: PendingIntentRecord{421ba7f0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452860959591, Int=0
,D/PMS     (  906): releaseWL(436a8938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/GLSUser ( 1376): GoogleAccountDataService.getToken()
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1376): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1376): GoogleAccountDataService.getToken()
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1376): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4134): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4134): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,D/ContactMessageStore( 1240): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1240): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1240): sku_id=99
D/ContactMessageStore( 1240): start background delete task...
,D/ContactMessageStore( 1240): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1240): size: 0 , 0
,D/ContactMessageStore( 1240): Background delete complete
,W/GLSUser ( 1376): GoogleAccountDataService.getToken()
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1376): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4134): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4134): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4134): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,D/PMS     (  906): acquireWL(4252f040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10073}
,V/AlarmManager(  906): sending alarm PendingIntent{41c23cc8: PendingIntentRecord{42e2db20 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452860974784, Int=0
,D/PMS     (  906): releaseWL(4252f040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4134): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  906): acquireWL(43ddc498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c7f9f8: PendingIntentRecord{42462c50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=638416, Int=0
,D/PMS     (  906): acquireWL(423bc5d0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): releaseWL(43ddc498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43210348): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(423bc5d0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(43210348): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(43195d90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=662348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43195d90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4260c350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4260c350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  906): killProcessQuiet, pid=4045
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4045:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4045
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(441aaf18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=722348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(441aaf18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4319ad28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4319ad28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4335cde0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=782348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4335cde0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/PMS     (  906): acquireWL(4314d668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d2a4b8: PendingIntentRecord{423fab70 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786349, Int=0
,D/PMS     (  906): releaseWL(4314d668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): acquireWL(4417ff70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4417ff70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(432af850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=842348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(432af850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42601f98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42601f98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(441c5088): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=902348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(441c5088): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4386a690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4386a690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42523e08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=962347, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42523e08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(424aa018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424aa018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(441cafe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{437ea208: PendingIntentRecord{4260de10 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452861260479, Int=1800000
,V/AlarmManager(  906): sending alarm PendingIntent{425b24d0: PendingIntentRecord{41f11f68 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452861278981, Int=900000
,V/AlarmManager(  906): sending alarm PendingIntent{425a4f80: PendingIntentRecord{43598ff0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452861349974, Int=0
,D/PMS     (  906): acquireWL(43318000): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1226 10028 null
,D/PMS     (  906): acquireWL(4424a730): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1226 10028 null
,W/ContextImpl( 4675): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(43318000): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 1226): Aggregate from 1452860448606 (log), 1452859460439 (data)
,D/PowerUsageService( 4675): call getInstance()
,D/SmartSyncUtils( 4675): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4675): MY_DEBUG = false
,D/PMS     (  906): releaseWL(441cafe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4394fc70): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4675 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4675): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4675): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4675): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4675): SettingOnTime = 1452924000000, randomSettingOnTime = 1452920903000
,D/SmartSyncScreenOnOffTimeReceiver( 4675): SettingOffTime = 1452902400000, randomSettingOffTime = 1452909001000
,D/SmartSyncScreenOnOffTimeReceiver( 4675): bDayMode = false
,W/BatSI   (  906): Couldn't get kernel wake lock stats
D/SmartSyncScreenOnOffTimeReceiver( 4675): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4675): bNightModeTurnOffOnce = false
,D/PMS     (  906): releaseWL(4394fc70): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  906): releaseWL(4424a730): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/PMS     (  906): acquireWL(439810d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{41f0ddb8: PendingIntentRecord{41d411a8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1012525, Int=0
,D/PMS     (  906): acquireWL(4238ed10): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1376 10028 null
,D/PMS     (  906): releaseWL(4238ed10): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  906): acquireWL(4327d820): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
,D/PMS     (  906): releaseWL(439810d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): releaseWL(4327d820): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): acquireWL(43c34ca0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10028 null
,D/GCM     ( 1376): Message class mow
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1376/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1376/10028)
,D/PMS     (  906): releaseWL(43c34ca0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): acquireWL(42602bb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
,D/PMS     (  906): releaseWL(42602bb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=4 [46][2][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42a6aad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1022348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42a6aad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425feee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425feee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425d76b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1082348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425d76b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425b5210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425b5210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425909f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/PMS     (  906): acquireWL(42588948): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{41c7f9f8: PendingIntentRecord{42462c50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1115510, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42573890): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(425909f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=12 [8][1][0]
D/PMS     (  906): acquireWL(420517a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(41fb4ef0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 906 1000 WorkSource{10160}
,E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1132): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42588948): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(42573890): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1132): nl80211: survey data missing!
E/wpa_supplicant( 1132): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1132): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(42287f38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42287f38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(41d85a38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(41d85a38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/dalvikvm-heap( 4169): Grow heap (frag case) to 15.197MB for 1821008-byte allocation
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(423f2400): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
I/NewsWeather( 4709): Last usage 0, idle 1452861453s, sync interval 2592000s
,I/NewsWeather( 4709): setPeriodicSync in seconds 2592000
D/PMS     (  906): releaseWL(423f2400): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4709): Skip sync for lookup editions
,I/NewsWeather( 4709): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4709): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,I/dalvikvm-heap( 4169): Grow heap (frag case) to 16.953MB for 1821008-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(44168f48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,W/GLSUser ( 1376): GoogleAccountDataService.getToken()
D/PMS     (  906): releaseWL(41fb4ef0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
D/PMS     (  906): releaseWL(44168f48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1376): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1570): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,E/NewsWeather( 4709): Unrecoverable authentication exception
E/NewsWeather( 4709): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4709): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4709): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4709): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4709): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e766a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 4709): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4709): [NET] getaddrinfo-,err=8
D/libc    ( 4709): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4709): [NET] getaddrinfo-, 1
,D/libc    ( 4709): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 11 5 12
D/libc    (  363): [NET] +++++ res_nsend xid =c425 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4709): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4709): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4709): [NET] getaddrinfo-,err=8
,E/NewsWeather( 4709): Failed to syncNewsAppData
,E/NewsWeather( 4709): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  906): acquireWL(424c8d58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
D/PMS     (  906): releaseWL(424c8d58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(420450c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 608919, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  906): releaseWL(420517a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): releaseWL(420450c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43326830): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1462/10028)
D/PMS     (  906): releaseWL(43326830): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1327): Unsupported attribute readOnly
,D/PMS     (  906): acquireWL(42431280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1142348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42431280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4315a4f8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/PMS     (  906): acquireWL(43320180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c7f9f8: PendingIntentRecord{42462c50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1145616, Int=0
,D/PMS     (  906): releaseWL(43320180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42e3d3f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4315a4f8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(42e3d3f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(42c542a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42c542a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(44198248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1202348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(44198248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4335ce90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4335ce90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(4256f590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c7f9f8: PendingIntentRecord{42462c50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1226354, Int=0
,D/PMS     (  906): acquireWL(42e72468): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/PMS     (  906): releaseWL(4256f590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43d6bd38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42e72468): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(43d6bd38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(42578250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1262348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42578250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e79778): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e79778): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42564f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1322348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42564f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4308c0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4308c0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(432af988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1382348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(432af988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e12770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e12770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42a636e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1442348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42a636e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(441c9ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(441c9ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4331ebd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(4331ebd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43328608): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1502347, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43328608): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e17658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e17658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(426119a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426119a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(431a4170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1562347, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(431a4170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(423ff888): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(423ff888): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(441cf560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(441cf560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42ec4118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1622348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42ec4118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e45070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42e45070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43cabad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1682348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43cabad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425e0a28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425e0a28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(433253a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(433253a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43483860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1742347, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43483860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e25bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e25bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(431b6648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PowerUI ( 1115): closing low battery warning: level=100
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/PMS     (  906): releaseWL(431b6648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(42c2bbe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1802348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42c2bbe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42c0a378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42c0a378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(4419f158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{41d2a4b8: PendingIntentRecord{423fab70 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1506378, Int=0
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,I/ProcessStatsService(  906): Prepared write state in 40ms
,I/ProcessStatsService(  906): Prepared write state in 27ms
,V/AlarmManager(  906): sending alarm PendingIntent{422d32a8: PendingIntentRecord{424c2868 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821328, Int=1800000
,D/PMS     (  906): acquireWL(43630698): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{425b24d0: PendingIntentRecord{41f11f68 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452862178981, Int=900000
,D/PMS     (  906): releaseWL(43630698): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2016-01-14-16-24-52.bin
,W/ContextImpl( 4675): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(4419f158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(435ba850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d5df98: PendingIntentRecord{41d567b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1862348, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(435ba850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4357b6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(4357b6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4826): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4826): ====startRecUseTime====
D/htc.customization.log.level( 4826):  is 
W/CustomizationLogLevel( 4826): Level value is invalid, use default level 2
D/CustomizationManager( 4826):  Read ACC file spent 0.125 (s)
D/CIDMapFileReader( 4826): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4826): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4826): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4826): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4826): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4826): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4826): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4826): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4826): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4826): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4826): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4826): Parsing tag category name = system
I/CustomizationCIDLoader( 4826): Parsing tag category name = application
I/CustomizationCIDLoader( 4826): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4826): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4826): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4826): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4826): Parsing tag category name = Settings
D/CustomizationManager( 4826):  Read CID file spent 0.179 (s)
D/CustomizationManager( 4826):  All configurations done spent 0.181 (s)
W/HtcNativeFlag( 4826): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4826): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4826): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4826): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4826, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
D/Process (  906): killProcessQuiet, pid=4460
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
D/Process (  906): killProcessQuiet, pid=4587
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4570
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4556
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Killing 4460:com.test.thalitest/u0a189 (adj 0): stop com.test.thalitest
I/ActivityManager(  906): Killing 4587:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1803s
I/ActivityManager(  906): Killing 4570:com.android.chrome/u0a96 (adj 15): empty for 1803s
I/ActivityManager(  906): Killing 4556:com.google.android.setupwizard/u0a78 (adj 15): empty for 1803s
D/Process (  906): killProcessQuiet, pid=3880
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4191
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4500
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Killing 3880:com.google.android.music:main/u0a154 (adj 15): empty for 1803s
I/ActivityManager(  906): Killing 4191:com.android.settings/1000 (adj 15): empty for 1803s
I/ActivityManager(  906): Killing 4500:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1810s
I/ActivityManager(  906):   Force finishing activity ActivityRecord{423ffe80 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  906): Copying FileAsset 0x69f6b4f8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  906): Recipient 4570
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4500
I/ActivityManager(  906): Recipient 4587
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
I/ActivityManager(  906): Recipient 4191
I/ActivityManager(  906): Recipient 4556
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3880
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.music (pid 3880): Died!
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 4460 uid 10189
I/WindowState(  906): WIN DEATH: Window{4257db00 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  906): Client connection lost with reason: 4
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1570): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1570): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/acms    ( 1896): Unregistering com.test.thalitest
E/acms    ( 1896): Could not unregister removed application com.test.thalitest
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): acquireWL(425f5708): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1462 10028 null
W/GeofencerStateMachine( 1462): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): releaseWL(425f5708): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/VoicemailCleanupService( 1299): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsRemoved
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
D/PackageBroadcastService( 1226): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
E/ExternalAccountType( 1327): Unsupported attribute readOnly
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4844 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/MultiDex( 4844): install
I/MultiDex( 4844): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/MultiDex( 4844): loading existing secondary dex files
I/MultiDex( 4844): load found 1 secondary dex files
I/MultiDex( 4844): install done
D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  906): Delaying start of: ServiceRecord{4425a970 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PeopleContactsSync( 1226): CP2 sync disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1226, uid=10028, userID:0
I/Icing   ( 1226): doRemovePackageData com.test.thalitest
D/PMS     (  906): acquireWL(43c5c1a8): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
D/PMS     (  906): releaseWL(43c5c1a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4863 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4844): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4863): install
I/MultiDex( 4863): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4863): loading existing secondary dex files
I/MultiDex( 4863): load found 1 secondary dex files
I/MultiDex( 4863): install done
I/ActivityManager(  906): Resuming delayed broadcast
I/ProviderInstaller( 4863): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/[PluginManager]RegisterService( 1414): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
E/SQLiteLog( 1414): (3850) statement aborts at 34: [DELETE FROM meta_data WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1414): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c9c69a8
W/[PluginManager]RegisterService( 1414): provider may killed!
W/[PluginManager]RegisterService( 1414): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1414): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1414): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1414): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1414): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1414): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
W/[PluginManager]RegisterService( 1414): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.delete(Unknown Source)
W/[PluginManager]RegisterService( 1414): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/[PluginManager]RegisterService( 1414): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
W/[PluginManager]RegisterService( 1414): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1414): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1414): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1414): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1414): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1414): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2897): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4882 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2897): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2897): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5ca3f008
W/dalvikvm( 2897): threadid=14: thread exiting with uncaught exception (group=0x41692e30)
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
E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2897): killProcess, pid=2897
E/SQLiteDatabase( 4844): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4844): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4844): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4844): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4844): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4844): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4844): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4844): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4844): threadid=12: thread exiting with uncaught exception (group=0x41692e30)
D/Process ( 2897): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4844): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4844): Process: com.google.android.gms.drive, PID: 4844
E/AndroidRuntime( 4844): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4844): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4844): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4844): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4844): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4844): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4844): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4844): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4844): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4844): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4844): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4844): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4844): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4844): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4844): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4844): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4844): 	at ctn.run(SourceFile:985)
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
D/Process ( 4844): killProcess, pid=4844
D/Process ( 4844): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
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
I/ActivityManager(  906): Recipient 2897
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.googlequicksearchbox:search (pid 2897) has died.
D/MediaRouterService(  906): Client com.google.android.googlequicksearchbox (pid 2897): Died!
D/WifiService(  906): Client connection lost with reason: 4
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10998ms
I/ActivityManager(  906): Recipient 4844
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4844) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10889ms
E/SQLiteDatabase( 4882): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4882): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4882): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4882): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4882): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4882): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4882): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4882): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4882): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4882): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4882): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4882): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4882): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4882): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4882): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4882): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4882): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4882): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4882): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4882): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4882): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4882): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4882): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4882): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4882): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4882): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4882): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4882): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4882): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4882): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4882): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4882): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4882): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4882): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4882): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4882): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4882): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4882): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4882): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4882): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4882): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4882): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4882): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4882): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4882): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4882): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4882): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4882): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4882): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4882): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4882): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4882): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4882): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4882): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4882): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4882): threadid=11: thread exiting with uncaught exception (group=0x41692e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4882): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4882): Process: com.google.android.apps.docs, PID: 4882
E/AndroidRuntime( 4882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4882): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4882): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4882): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4882): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4882): 	at aho.run(AbstractDatabaseInstance.java:455)
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
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4902 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4882): killProcess, pid=4882
D/Process ( 4882): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Recipient 4882
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4882) has died.
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41b55dd0 +
I/Prism.WidgetManager( 1273): onLoadItems() +
W/ContextImpl( 4902): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4902): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4902): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4902): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4902): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4902): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4902): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4902): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4902): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4902): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4902): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4902): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4902): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4902): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4902): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4902): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4902): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4902): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4902): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4902): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4902): threadid=10: thread exiting with uncaught exception (group=0x41692e30)
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4915 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  906): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4902): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4902): Process: com.android.keychain, PID: 4902
E/AndroidRuntime( 4902): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4902): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4902): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4902): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4902): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4902): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4902): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4902): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4902): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4902): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4902): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4902): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4902): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4902): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4902): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4902): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4902): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4902): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4915): getInstance(Context context)
D/AppTag  ( 4915): getInstance(Context context)
D/AppTag  ( 4915): onCreate()
D/Process ( 4902): killProcess, pid=4902
D/Process ( 4902): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452862254789.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  906): Recipient 4902
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.keychain (pid 4902) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10281ms
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(425c8fd8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4169 10160 null
D/PMS     (  906): releaseWL(425c8fd8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  906): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=4931 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}

```
