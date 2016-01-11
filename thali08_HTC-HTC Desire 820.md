#### Test 549702617e2936d_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 168
D/WifiNative-wlan0(  902): doBoolean: SignalStrength 97
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  902):    returned true
E/cutils-trace( 4390): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4390): ====startRecUseTime====
D/htc.customization.log.level( 4390):  is 
W/CustomizationLogLevel( 4390): Level value is invalid, use default level 2
D/CustomizationManager( 4390):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4390): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4390): Parsing tag category name = system
I/CustomizationCIDLoader( 4390): Parsing tag category name = application
I/CustomizationCIDLoader( 4390): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4390): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4390): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4390): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4390): Parsing tag category name = Settings
D/CustomizationManager( 4390):  Read CID file spent 0.089 (s)
D/CustomizationManager( 4390):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 4390): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4390): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4390): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4390): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  902): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  902): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  902): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  902): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  902): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  902): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  902): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4390
D/PMS     (  902): acquireHCC(4231e068): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 902 1000 null
D/PMS     (  902): acquireHCC(422c9b48): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 902 1000 null
I/Intent  (  902): @test_code: getHtcIntentFlag: 0 obj: 1110795336
D/PMS     (  902): acquireWL(41d0cd30): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 902 1000 null
I/FeedHostManager( 1267): [onPause]
I/FeedProviderManager( 1267): onPause
I/FeedHostManager( 1267): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c8fcd0
I/SocialFeedProvider( 1267): +onPause
I/SocialFeedProvider( 1267): -onPause
I/ActivityManager(  902): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4401 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1267): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4401): Binding Chromium to main looper Looper (main, tid 1) {41a926f8}
I/LibraryLoader( 4401): Expected native library version number "",actual native library version number ""
I/chromium( 4401): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4401): Initializing chromium process, renderers=0
D/PMS     (  902): acquireWL(424997a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  902): acquireWL(423e4bc0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/BluetoothManagerService(  902): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  902): java.lang.Throwable: stack dump
D/BluetoothManagerService(  902): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@422d3d08:true
W/System.err(  902): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  902): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  902): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  902): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  902): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4401): 1101709576: getState(). Returning 12
D/PMS     (  902): releaseWL(424997a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4401): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4401): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4401): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4401): Local Branch: 
I/Adreno-EGL( 4401): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4401): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4401):                  aa63bbd948f41d15fc72f585e
W/chromium( 4401): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
D/PMS     (  902): acquireWL(42351d38): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
W/dalvikvm( 4401): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4401): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4401): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4401): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4401): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4401): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4401): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4401): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4401): CordovaWebView is running on device made by: HTC
D/PMS     (  902): releaseWL(42351d38): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(423796f8): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  902): releaseWL(423796f8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(422c1338): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  902): releaseWL(422c1338): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  902): acquireWL(43f95040): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  902): releaseWL(43f95040): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/AwContents( 4401): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  902): Displayed com.test.thalitest/.MainActivity: +283ms
W/ResourceType( 4401): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4401): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41add7f8, mServedView=org.apache.cordova.engine.SystemWebView{41aa3420 VFEDH.C. .F...... 0,0-720,1134 #64}
W/XT9_C   ( 1205): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1205): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  902): Disable input method client, pid=1267
I/InputMethodManagerService(  902): Enable input method client, pid=4401
D/PMS     (  902): releaseWL(41d0cd30): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4401): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4401): JniHelper::setJavaVM(0x4156c048), pthread_self() = 1662533280
,D/JX-Cordova( 4401): jxcore cordova android initializing
,I/SensorManager(  902): mEventCount = 1050
,I/SensorManager(  902): mEventCount = 1050
,I/dalvikvm-heap( 4401): Grow heap (frag case) to 11.582MB for 95956-byte allocation
,I/dalvikvm-heap( 4401): Grow heap (frag case) to 11.661MB for 143930-byte allocation
,I/dalvikvm-heap( 4401): Grow heap (frag case) to 11.775MB for 215890-byte allocation
,I/dalvikvm-heap( 4401): Grow heap (frag case) to 11.951MB for 323830-byte allocation
,I/dalvikvm-heap( 4401): Grow heap (frag case) to 12.223MB for 485740-byte allocation
,I/dalvikvm-heap( 4401): Grow heap (frag case) to 13.223MB for 1092904-byte allocation
,I/dalvikvm-heap( 4401): Grow heap (frag case) to 14.109MB for 1639352-byte allocation
,I/dalvikvm-heap( 4401): Grow heap (frag case) to 15.446MB for 2459024-byte allocation
,I/dalvikvm-heap( 4401): Grow heap (frag case) to 17.471MB for 3688532-byte allocation
,W/CpuWake (  902): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  902): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  902): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  902): <<release mCpuPerf_cpu_count wakelock
,W/CpuWake (  902): >>release mCpuPerf_Freq wakelock
W/CpuWake (  902): <<release mCpuPerf_Freq wakelock
,D/PMS     (  902): releaseHCC(4231e068): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,W/jxcore-log( 4401): Initializing JXcore engine
,W/jxcore-log( 4401): JXcore engine is ready
D/PMS     (  902): releaseHCC(422c9b48): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4401): Starting JXcore engine
,W/jxcore-log( 4401): Platform android
W/jxcore-log( 4401): 
,W/jxcore-log( 4401): Process ARCH arm
W/jxcore-log( 4401): 
,I/ActivityManager(  902): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4449 uid=10077 gids={50077}
,D/PMS     (  902): acquireWL(422da2c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10077}
,V/AlarmManager(  902): sending alarm PendingIntent{425682b8: PendingIntentRecord{4260fe48 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452525655135, Int=60000
,D/PMS     (  902): releaseWL(422da2c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4449): SMSBackupAgentService started
,D/SMSBackup( 4449): Checking restore status
D/SMSBackup( 4449): Restore complete
,D/SMSBackup( 4449): cancelCheckAlarm,
,D/SMSBackup( 4449): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  902): killProcessQuiet, pid=3587
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3587:com.htc.task/u0a70 (adj 15): empty #17
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Recipient 3587
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 192
,D/WifiNative-wlan0(  902): doBoolean: SignalStrength 97
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  902):    returned true
,I/jxcore-log( 4401): JXcore Cordova bridge is ready!
I/jxcore-log( 4401): 
,W/jxcore-log( 4401): JXcore engine is started
,I/chromium( 4401): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WifiDataStallTracker(  902): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  902): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  902): acquireWL(422fcfb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
V/AlarmManager(  902): sending alarm PendingIntent{422abc68: PendingIntentRecord{4252a750 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=104397, Int=0
D/WifiDataStallTracker(  902): updateDataStallInfo: mDataStallTxRxSum={txSum=46 rxSum=36} preTxRxSum={txSum=45 rxSum=35}
D/WifiDataStallTracker(  902): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  902): onDataStallAlarm: tag=19382 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  902): startDataStallAlarm: tag=19383 delay=15s
D/PMS     (  902): releaseWL(422fcfb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4401): Toggling radios to true
I/jxcore-log( 4401): 
,D/BluetoothAdapter( 4401): enable(): BT is already enabled..!
,D/WifiManager( 4401): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  902): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  902): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  902): Settings:Agentvalue: 2
W/Settings:Agent(  902): >> traceCallingStack()
W/Settings:Agent(  902): Process.myPid(): 902
W/Settings:Agent(  902): Process.myTid(): 1342
W/Settings:Agent(  902): Process.myUid(): 1000
W/Settings:Agent(  902): 
W/Settings:Agent(  902): 
W/System.err(  902): java.lang.Throwable: stack dump
W/System.err(  902): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  902): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  902): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  902): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  902): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  902): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  902): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  902): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  902): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  902): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  902): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  902): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  902): 
W/Settings:Agent(  902): << traceCallingStack(): 1(ms)
D/WifiManager( 4401): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  902): doBoolean: DISCONNECT
D/WifiManager( 4401): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): TDLS: Tear down peers
,I/wpa_supplicant( 1161): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiService(  902): setWifiEnabled: true pid=4401, uid=10348
D/WifiService(  902): New client listening to asynchronous messages
E/WifiService(  902): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  902): isSprintWifiRestricted(): false
I/WifiService(  902): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  902): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4401): Radios toggled
I/jxcore-log( 4401): 
I/jxcore-log( 4401): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4401): 
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1161): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1161): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1161): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  902): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1161): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8de9bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1161):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1161): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1161): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1161): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1161): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1161): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1161): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1161): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1161): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1161): nl80211:, if_removed already cleared - ignore event
D/wpa_supplicant( 1161): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1161): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1161): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1161): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1161): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  902): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  902): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getReasonFromEventString() 3
D/Tethering(  902): interfaceLinkStateChanged wlan0, false,
D/WifiNative-wlan0(  902):    returned true
D/Tethering(  902): interfaceStatusChanged wlan0, false
D/HTCRequest(  902): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/WifiPerfLock(  902): release()
D/HTCRequest(  902): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/WifiStateMachine(  902): PerfLock released for exiting ConnectedState
D/HTCRequest(  902): WifiMonitor:getFreqFromEventString() 2412
,D/WifiMonitor(  902): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/Tethering(  902): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  902): doBoolean: DRIVER POWERMODE 0
D/Tethering(  902): interfaceLinkStateChanged wlan0, false
,D/Tethering(  902): interfaceStatusChanged wlan0, false
D/Tethering(  902): [isWifi] getHotspotEnabled: false
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Power_Mode_Type mode = 0
I/wpa_supplicant( 1161): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  902):    returned true
D/WifiNative-wlan0(  902): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  902):    returned true
,D/DhcpStateMachine(  902): [RunningState] Stop DHCP
,D/libc    (  902): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/ConnectivityService(  902): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  902): acquireWL(4241be68): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 902 1000 null
D/WifiP2pService(  902): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  902): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  902): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  902): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  902): doBoolean: RECONNECT
D/WifiDataStallTracker(  902): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  902): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/WifiDataStallTracker(  902): stopDataStallAlarm: current tag=19383 mDataStallAlarmIntent=PendingIntent{42db24c0: PendingIntentRecord{4252a750 android broadcastIntent}}
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): Fast associate: Old scan results
I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/libc    (  902): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  902):    returned true
D/WifiStateMachine(  902): Enter handleNetworkDisconnect
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiStateTracker(  902): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  902): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  902): Provision feature enable=false
D/ConnectivityService(  902): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiNative-wlan0(  902): doBoolean: DRIVER POWERMODE 0
D/UsbnetStateTracker(  902): isAvailable+-
D/UsbnetStateTracker(  902): reconnect
,D/UsbnetStateTracker(  902): isAvailable+-
D/WISPrService( 4177): >>>>>WISPrService start isConnected = false<<<<<
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Power_Mode_Type mode = 0
I/wpa_supplicant( 1161): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  902):    returned true
D/WifiNative-wlan0(  902): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  902):    returned true
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  902): default: reconnect()
D/MDST    (  902): default: setTeardownRequested(false)
D/MDST    (  902): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  902): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  902): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  902): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  902): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/WISPrService( 4177): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  902): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  902): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  902): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  902): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  902): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiService(  902): New client listening to asynchronous messages
W/ConnectivityService(  902): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  902): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  902): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  902): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
,D/ConnectivityService(  902): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] entry_id:5   entry:0xb7a9acf8  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb7aa3e80  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb7aa3f68  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb7a9f3a0  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb7a9f530  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb7a9a8f0  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb7a9f458  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
W/ConnectivityService(  902): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  902): handleConnectivityChange: resetting
D/ConnectivityService(  902): resetConnections(wlan0, 3)
D/WifiStateTracker(  902): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/PMS     (  902): acquireWL(42586498): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1362 10028 null
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
D/ConnectivityService(  902): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  902): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  902): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WISPrService( 4177): >>>>>WISPrService start isConnected = false<<<<<
D/WirelessDisplayService(  902): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  902): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  902): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4177): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/PMS     (  902): acquireWL(42389f58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
D/ConnectivityService(  902): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  902): acquireWL(422adac8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 902 1000 null
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by  (902/1000)
D/ConnectivityService(  902): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  902): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/WifiStateMachine(  902): startScan Pid: 902 Uid 1000
,I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiNative-wlan0(  902): doBoolean: SCAN
D/PMS     (  902): releaseWL(42389f58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  902): reportInetCondition for net -1, percentage: 0 by  (1362/10028)
D/PMS     (  902): releaseWL(42586498): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/BatSI   (  902): WIFI scan started for: 650a0300 uid:1000
I//system/bin/ip(  364): RTNETLINK answers: No such process
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  902):    returned false
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1362/10028)
D/PMS     (  902): releaseWL(422adac8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  902): releaseWL(423e4bc0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/ConnectivityService(  902): mActiveDefaultNetwork: -1
D/ConnectivityService(  902): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:0
,V/Tethering(  902): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  902): [AlarmQueuing] connectivity wifi: false
D/GpsLocationProvider(  902): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  902): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  902): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  902): ignore wifi update if we are not in OPENING or CLOSING
,D/Tethering(  902): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  902): bSetPropertyMultiRAB:false
,D/CaptivePortalTracker(  902): DelayedCaptiveCheckState
D/Tethering(  902): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  902): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  902): ipv4Default null
,I/Tethering(  902): No IPv4 upstream interface, giving up.
D/Tethering(  902): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1267): [onReceive] WIFI(1): DISCONNECTED
I/NetworkMonitor( 3846): type=WIFI subType= reason=null isConnected=false
D/CaptivePortalTracker(  902): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  902): NoActiveNetworkState
D/htcCheckinService(  902): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  902): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by  (902/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
D/PMS     (  902): acquireWL(42510250): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 902 1000 null
D/PMS     (  902): releaseWL(42510250): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1435/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by com.htc.launcher (1267/10075)
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by com.google.android.music (3846/10154)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1895/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.docs (4290/10100)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.docs (4290/10100)
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (2424/10021)
,I/ActivityManager(  902): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4472 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4472): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4472): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4472): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4472): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4472): Preparing secondary program dexes.
V/DexLibLoader( 4472): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4472): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4472): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4472): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4472): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4472): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4472): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4472): Dex already copied
D/OdexVerifier( 4472): Odex verification is skipped.
,V/DexLibLoader( 4472): Creating class loader
,V/DexLibLoader( 4472): Finished creating class loader
V/DexLibLoader( 4472): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4472): Dex already copied
D/OdexVerifier( 4472): Odex verification is skipped.
,V/DexLibLoader( 4472): Creating class loader,
V/DexLibLoader( 4472): Finished creating class loader
V/DexLibLoader( 4472): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar,
V/DexLibLoader( 4472): Dex already copied
D/OdexVerifier( 4472): Odex verification is skipped.
,V/DexLibLoader( 4472): Creating class loader,
V/DexLibLoader( 4472): Finished creating class loader,
V/DexLibLoader( 4472): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4472): Dex already copied
D/OdexVerifier( 4472): Odex verification is skipped.
,V/DexLibLoader( 4472): Creating class loader,
V/DexLibLoader( 4472): Finished creating class loader
,V/DexLibLoader( 4472): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4472): DexLibLoader.ensureDexLoaded took 21 ms
,W/dalvikvm( 4472): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4472): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4472): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4472): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4472): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4472): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4472): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4472): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4472): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-73
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1161): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1161): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1161): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1161): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1161): Add randomness: count=11 entropy=5
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 3
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 1
I/wpa_supplicant( 1161): wpa_s->is_screen_on 1
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): selected network = 1
D/wpa_supplicant( 1161): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8deb4e8  current_ssid=0x0
D/wpa,_supplicant( 1161): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1161): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1161): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1161): check if in concurrent case
I/wpa_supplicant( 1161): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1161): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1161): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1161): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1161): RSN: PMKSA cache search - network_ctx=0xb8deb4e8 try_opportunistic=0
D/wpa_supplicant( 1161): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1161): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1161): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1161): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1161): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1161): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1161): nl80211: Unsubscribe mgmt frames handle 0xb8dea718 (mode change)
D/wpa_supplicant( 1161): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8dea718
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8dea718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8dea718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8dea718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8dea718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8dea718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8dea718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8dea718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8dea718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8dea718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb8dea718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1161):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1161):   * freq=2412
D/wpa_supplicant( 1161):   * Auth Type 0
D/wpa_supplicant( 1161):   * WPA Versions 0x2,
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1161): nl80211: Connect request send successfully
D/wpa_supplicant( 1161): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18,
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  902): doString: LIST_DONGLES,
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,D/WifiNative-wlan0(  902): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (779) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-47
I/wpa_supplicant( 1161): tsf=0000000106751223
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-55
I/wpa_supplicant( 1161): tsf=0000000106751241
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2452
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000106751245
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=3
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-55
I/wpa_supplicant( 1161): tsf=0000000106751236
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-85
I/wpa_supplicant( 1161): tsf=0000000106751249
I/wpa_supplicant( 1161): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=5
I/wpa_supplicant( 1161): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-85
I/wpa_supplicant( 1161): tsf=0000000106751252
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC5999698
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  902): getDiscoveryDongleList
D/WifiStateMachine(  902): == begin of scan result ==
,D/WifiStateMachine(  902): == (6) end of scan result ==
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/WifiStateMachine(  902): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 106751223, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 106751241, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2452, timestamp: 106751245, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 106751236, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 106751249, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 106751252, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): add 6 to mScanResults
D/BatSI   (  902): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  902): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  902): getDiscoveryDongleList
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,E/FbInjectorInitializer( 4472): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1161): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1161): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1161): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1161): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1161): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1161): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1161): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1161): nl80211: Connect event
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1161): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1161): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1161): Add randomness: count=12 entropy=6
I/wpa_supplicant( 1161): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1161): TDLS: Remove peers on association
D/wpa_supplicant( 1161): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1161): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1161): EAPOL: enable timer tick
D/wpa_supplicant( 1161): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1161): htc_wext_set_keepalive +
I/wpa_supplicant( 1161): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1161): getPrivFuncNum +	
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 1161): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1161): htc_wext_set_keepalive fnum = 0x8bf6
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 1161): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1161): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1161): Get randomness: len=32 entropy=7
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  902): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  902): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  902): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  902): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  902): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  902): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  902): WifiMonitor:handleSupplicantSt,ateChange(): SSIDNG700
D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  902): Enter handleAssociatedWithEvent
D/WifiStateMachine(  902): Associated
D/Tethering(  902): interfaceLinkStateChanged wlan0, false
D/Tethering(  902): interfaceStatusChanged wlan0, false
D/Tethering(  902): [isWifi] getHotspotEnabled: false
D/Tethering(  902): interfaceLinkStateChanged wlan0, true
D/Tethering(  902): interfaceStatusChanged wlan0, true
D/Tethering(  902): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  902): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  902): Exit handleAssociatedWithEvent
D/WifiStateMachine(  902): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  902): updateConnectedAP...
,D/WifiApDatabaseHandler(  902): updateConnectedAP...
,D/WifiStateMachine(  902): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 1161): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiApDatabaseHandler(  902): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  902): This record is existed, only update it...
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8dea9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1161):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 11
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1161): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fa1b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1161):    broadcast key
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1161): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiApDatabaseHandler(  902): updateConnectedAP...
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1161): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1161): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1161): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1161): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP),
D/wpa_supplicant( 1161): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1161): set send_ind_to_ndc = 0
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=1
,D/wpa_supplicant( 1161): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1161): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1161): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1161): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1161): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Authorized
,D/wpa_supplicant( 1161): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  902): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1161): EAPOL authentication completed successfully,
I/wpa_supplicant( 1161): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1161): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1161): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1161): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  902): interfaceLinkStateChanged wlan0, true
D/Tethering(  902): interfaceStatusChanged wlan0, true
,D/Tethering(  902): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
,D/WifiApDatabaseHandler(  902): updateConnectedAP...,
,D/WifiStateMachine(  902): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  902): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  902): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  902): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  902): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  902): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  902): This record is existed, only update it...
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  902): updateConnectedAP...
D/WifiStateTracker(  902): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  902): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  902): Provision feature enable=false
D/ConnectivityService(  902): mActiveDefaultNetwork: -1
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 4177): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4177): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  902): updateConnectedAP...
,D/DhcpStateMachine(  902): [StoppedState] Start DHCP
,D/WifiStateMachine(  902): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  902): doBoolean: SignalStrength 97
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  902):    returned true
,D/WifiNative-wlan0(  902): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  902):    returned true
,D/WifiNative-wlan0(  902): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Power_Mode_Type mode = 1
I/wpa_supplicant( 1161): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  902):    returned true
,D/WifiNative-wlan0(  902): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  902):    returned null
E/WifiStateMachine(  902): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  902): doString: DRIVER WLS_BATCHING STOP
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  902):    returned null
,W/fb4a(:<default>):StaticBindingVerifier( 4472): Verify
D/WifiStateMachine(  902): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  902): acquireWL(43f88e60): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 902 1000 null
D/WifiStateMachine(  902): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  902): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42517158 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42517158 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiService(  902): New client listening to asynchronous messages
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4472): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4472): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  902): killProcessQuiet, pid=3154
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  902): Killing 3154:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3154
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  902): acquireWL(4238f978): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
,D/PMS     (  902): acquireWL(42db7e60): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1226 10028 null
,D/PMS     (  902): releaseWL(4238f978): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/PMS     (  902): releaseWL(42db7e60): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1362): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/AutoSetting( 1398): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  902): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4501 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.sense.hsp (1398/10053)
,D/AutoSetting( 1398): Util - no network available!
,D/AutoSetting( 1398): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1398): service - mHandler: cancel location update
,D/AutoSetting( 1398): service -           changes count: 0
D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.sense.hsp (1398/10053)
,W/fb4a(:<default>):UserScope( 4472): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4472): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4472): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4501): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4501): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4501): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4501): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  902): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4515 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  902): killProcessQuiet, pid=3829
,I/ActivityManager(  902): Killing 3829:com.htc.mediamanager/u0a32 (adj 15): empty #17
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.setupwizard (4501/10078)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.setupwizard (4501/10078)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.setupwizard (4501/10078)
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4472): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/libc    (  902): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent DefaultState
,I/ActivityManager(  902): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4539 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  902): killProcessQuiet, pid=4232
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  902): Killing 4232:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3829
,E/dalvikvm( 4472): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4472): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/dalvikvm( 4472): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4472): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4472): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4472): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4472): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4472): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4472): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4472): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4472): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
I/ActivityManager(  902): Recipient 4232
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  902): Client connection lost with reason: 4
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 9.962MB for 84664-byte allocation
,W/dalvikvm( 4472): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4472): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4472): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4472): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4472): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4472): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4472): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4539): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4539): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4539): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4539): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4539): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/dalvikvm-heap( 4472): Grow heap (frag case) to 9.976MB for 28144-byte allocation
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 10.017MB for 39954-byte allocation
,D/libc    (  902): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-, SUCCESS
D/libc    (  902): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-, SUCCESS
D/libc    (  902): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-, SUCCESS
,D/libc    (  902): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-, SUCCESS
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 10.093MB for 79892-byte allocation
,D/WifiNative-wlan0(  902): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1161): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  902):    returned true
D/WifiNative-wlan0(  902): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  902):    returned true
,D/WifiStateMachine(  902): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  902): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  902): releaseWL(43f88e60): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [1][0][0]
,I/wpa_supplicant( 1161): Change stage from stage0 to stage3
,D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  902): doBoolean: SignalStrength 97
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  902):    returned true
,D/WifiStateMachine(  902): gateway: /192.168.1.1
,D/WifiNative-wlan0(  902): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1161): wlan0: Background scan every 600 seconds
D/WifiNative-wlan0(  902):    returned true
D/WIFI_ICON( 1112): updateWifiState: RSSI_CHANGED -1 -> 3
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.magazines (4539/10151)
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  902): VerifyingLinkState enter
D/WifiStateMachine(  902): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  902): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  902): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  902): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -55, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
V/WebViewChromiumFactoryProvider( 4539): Binding Chromium to main looper Looper (main, tid 1) {41a9b2e0}
D/WifiDataStallTracker(  902): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  902): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
I/LibraryLoader( 4539): Expected native library version number "",actual native library version number ""
D/WifiDataStallTracker(  902): startDataStallAlarm: tag=19385 delay=15s
I/chromium( 4539): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4539): Initializing chromium process, renderers=0
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  902): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiWatchdogStateMachine(  902): WAN detection
,D/WISPrService( 4177): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiStateTracker(  902): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  902): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  902): Provision feature enable=false
D/ConnectivityService(  902): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  902): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  902): default: teardown()
D/MDST    (  902): default: setTeardownRequested(true)
D/MDST    (  902): default: setEnableApn apnType =default , enable=false
D/libc    (  902): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-, SUCCESS
D/MDST    (  902): default: setTeardownRequested(true)
D/ConnectivityService(  902): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  902): Unexpected mtu value: android.net.wifi.WifiStateTracker@423c3280
D/ConnectivityService(  902): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/PMS     (  902): acquireWL(431265a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  902): acquireWL(43173c80): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  902): releaseWL(431265a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
E/AudioManagerAndroid( 4539): BLUETOOTH permission is missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  902): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  902): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  902): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  902): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,I/Adreno-EGL( 4539): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4539): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4539): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4539): Local Branch: 
I/Adreno-EGL( 4539): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4539): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4539):                  aa63bbd948f41d15fc72f585e
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  902): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  902): handleConnectivityChange: resetting
D/Nat464Xlat(  902): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  902): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  902): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  902): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  902): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  902): acquireWL(43eda478): PARTIAL_WAKE_LOCK  NetworkStats 0x1 902 1000 null
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [1][0][0]
,D/WirelessDisplayService(  902): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  902):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by  (902/1000)
D/ConnectivityService(  902): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.setupwizard (4501/10078)
I/QuickSettingWifi( 1112): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/PMS     (  902): acquireWL(4324b158): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/PMS     (  902): releaseWL(43eda478): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  902): acquireWL(43fdd818): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1226 10028 null
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,I/NSApplication( 4539): Starting up...
D/PMS     (  902): releaseWL(4324b158): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,I/CheckinService( 1226): Preparing to send checkin request
,I/EventLogService( 1226): Accumulating logs since 1452525605691
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.magazines (4539/10151)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.magazines (4539/10151)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 10.280MB for 75760-byte allocation
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/Process (  902): killProcessQuiet, pid=4260
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.plus (4154/10160)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.plus (4154/10160)
D/ConnectivityService(  902): mActiveDefaultNetwork: WIFI
,I/ActivityManager(  902): Killing 4260:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/GoogleHttpClient( 1226): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1226): Using GMS GoogleHttpClient
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
I/ActivityManager(  902): Recipient 4260
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
W/BroadcastQueue(  902): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4318f6e0 u0 ReceiverList{4318f5e0 4472 com.facebook.katana/10026/u0 remote:430fea70}}
W/BroadcastQueue(  902): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4318f6e0 u0 ReceiverList{4318f5e0 4472 com.facebook.katana/10026/u0 remote:430fea70}}
W/BroadcastQueue(  902): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43660f80 u0 ReceiverList{43660f20 4472 com.facebook.katana/10026/u0 remote:4365fe38}}
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  902): getNetworkInfo networkType=9 called by com.google.android.gms (1226/10028)
D/ConnectivityService(  902): getNetworkInfo networkType=0 called by com.google.android.gms (1226/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
,D/PMS     (  902): acquireWL(43f69a90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1435 10028 null
,D/PMS     (  902): releaseWL(43f69a90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/wpa_supplicant( 1161): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1161): EAPOL: disable timer tick
,D/GCoreFlp( 1435): Unknown pending intent to remove.
,W/GLSUser ( 1362): GoogleAccountDataService.getToken()
D/PMS     (  902): acquireWL(44633450): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1435 10028 null
D/PMS     (  902): releaseWL(44633450): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1588): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1588): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1226): awaiting user notification for token
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41f6e8d0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.google.android.gms 1 19 3 12
,I/ActivityManager(  902): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4610 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4472): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4472): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/MultiDex( 4610): install
,I/MultiDex( 4610): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4610): loading existing secondary dex files
,I/MultiDex( 4610): load found 1 secondary dex files
,I/MultiDex( 4610): install done
,I/ProviderInstaller( 4610): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/PMS     (  902): acquireWL(43a47450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{42089898: PendingIntentRecord{42326528 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=108548, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
D/PMS     (  902): releaseWL(43a47450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1112): WifiActivity: 3
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/PMS     (  902): releaseWL(4241be68): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  902): NetTransition Wakelock for ConnectedState released by timeout
,I/ClockThread( 1112): now=1452525660055 next=59945
,V/Tethering(  902): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/CaptivePortalTracker(  902): NoActiveNetworkState
D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  902): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.musicenhancer (3882/10051)
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by  (902/1000)
,I/NetworkMonitor( 3846): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  902): DelayedCaptiveCheckState
,I/ConnectivityHelper( 1267): [onReceive] WIFI(1): CONNECTED
,I/acms    ( 1895): Checking Certificates
I/acms    ( 1895): Checking Developer Certificates
I/acms    ( 1895): Checking Application Certificates
I/acms    ( 1895): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1895): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1895): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by com.google.android.music (3846/10154)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.setupwizard (4501/10078)
D/ConnectivityService(  902): getNetworkInfo networkType=1 called by com.htc.launcher (1267/10075)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/PMS     (  902): acquireWL(434e5af0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 902 1000 null
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.docs (4290/10100)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1895/1000)
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
I/acms    ( 1895): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1895): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1895): Updating next query delay: 75600000
I/mlserverapp( 1895): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1895): cancelACMSProgrammedChecks
D/htcCheckinService(  902): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  902): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,V/Tethering(  902): bSetPropertyMultiRAB:false
W/Settings( 4610): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Tethering(  902): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  902): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  902): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  902): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  902): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  902): Found interface wlan0
,D/Tethering(  902): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1435/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/PMS     (  902): acquireWL(4339a3c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 902 1000 null
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.docs (4290/10100)
D/GpsLocationProvider(  902): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  902): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  902): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  902): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  902): releaseWL(4339a3c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/PMS     (  902): releaseWL(434e5af0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  902): getActiveNetworkInfo called by  (2424/10021)
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/PMS     (  902): acquireWL(41ee5e08): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
,D/PMS     (  902): releaseWL(41ee5e08): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1362): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1362/10028)
D/libc    ( 1362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1362): [NET] getaddrinfo-,err=8
D/libc    ( 1362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1362): [NET] getaddrinfo-, 1
D/libc    ( 1362): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =1562 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1362/10028)
D/PMS     (  902): acquireWL(423878c8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1362 10028 null
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/AutoSetting( 1398): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4501): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4501): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.sense.hsp (1398/10053)
,D/AutoSetting( 1398): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1398): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1398): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1398): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1398): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1398): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.magazines (4539/10151)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.sense.hsp (1398/10053)
D/AutoSetting( 1398): service - handleMessage() setting current location null
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.plus (4154/10160)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.apps.plus (4154/10160)
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  902): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  902): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent DefaultState
D/ConnectivityService(  902): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 252
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1362): [NET] getaddrinfo_proxy-, success
,I/dalvikvm-heap( 4154): Grow heap (frag case) to 13.500MB for 1821008-byte allocation
,D/libc    ( 1362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1362): [NET] getaddrinfo-,err=8
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1362/10028)
D/PMS     (  902): acquireWL(42619190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
D/PMS     (  902): releaseWL(42619190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/Adreno-EGL( 4610): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4610): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4610): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4610): Local Branch: 
I/Adreno-EGL( 4610): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4610): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4610):                  aa63bbd948f41d15fc72f585e
,D/GCM     ( 1362): Connected
D/PMS     (  902): acquireWL(424261b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1362 10028 null
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1362/10028)
D/PMS     (  902): releaseWL(423878c8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  902): reportInetCondition for net 1, percentage: 100 by  (1362/10028)
D/ConnectivityService(  902): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  902): handleInetConditionChange: starting a change hold
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1362/10028)
D/PMS     (  902): releaseWL(424261b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  902): acquireWL(4206e9b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1362 10028 null
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (1362/10028)
,D/ConnectivityService(  902): reportInetCondition for net 1, percentage: 100 by  (1362/10028)
D/ConnectivityService(  902): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1362): Message class mpf
,I/Adreno-EGL( 4610): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4610): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4610): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4610): Local Branch: 
I/Adreno-EGL( 4610): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4610): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4610):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  902): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  902): reportInetCondition for net 1, percentage: 100 by  (1362/10028)
D/ConnectivityService(  902): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  902): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1362/10028)
D/PMS     (  902): releaseWL(4206e9b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  902): acquireWL(4304d9d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
D/PMS     (  902): releaseWL(4304d9d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/Adreno-EGL( 4610): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4610): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4610): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4610): Local Branch: 
I/Adreno-EGL( 4610): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4610): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4610):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (4610/10028)
,I/CheckinTask( 1226): Sending checkin request (8889 bytes)
D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1226): [NET] getaddrinfo-, 1
,D/libc    ( 1226): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =d358 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 237
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1226): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  902): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  902): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=4 [22][1][0]
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  902): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/PMS     (  902): acquireWL(43f79218): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
,D/PMS     (  902): releaseWL(43f79218): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  902): getNetworkInfo networkType=9 called by com.google.android.gms (1226/10028)
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [2][0][0]
D/ConnectivityService(  902): getNetworkInfo networkType=0 called by com.google.android.gms (1226/10028)
,W/GLSUser ( 1362): GoogleAccountDataService.getToken()
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1588): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1588): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1226): awaiting user notification for token
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41b22ca0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.google.android.gms 2 10 2 12
,I/CheckinTask( 1226): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1226): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  902): releaseWL(43fdd818): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1226): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c62840 that was originally bound here
E/ActivityThread( 1226): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c62840 that was originally bound here
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
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
,I/GCM     ( 1362): GCM config loaded
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
,W/fb4a(:<default>):UserScope( 4472): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4472): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 168
D/WifiStateMachine(  902): BroadcastRSSIForIMS, newrssi =-56 , oldRssi= -200
,D/WifiNative-wlan0(  902): doBoolean: SignalStrength 97
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  902):    returned true
D/WIFI_ICON( 1112): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/fb4a(:<default>):LocalFbBroadcastManager( 4472): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
,I/PMS     (  902): Going to sleep due to screen timeout...
,I/ActivityManager(  902): mThumbnailWidth=360, mThumbnailHeight=640
V/LightsService(  902): setLight #2: color=#0
D/qdlights(  902): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  902): setLight #0: color=#0
,I/SensorManager(  902): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420d93c8
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  902): disable: get sensor name = CM36282 Light sensor
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 2
W/SensorService(  902): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  902): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  902): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420d93c8, eanble = 0, strlen(mName) = 59
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  902): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421548b0
W/SensorService(  902): Listener[1] = com.htc.smartdim.sensor_eye@4260efc0
,W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  902): Couldn't get kernel wake lock stats
,W/PMS     (  902): mWirelessDisplayManager is null
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
,D/WirelessDisplayService(  902): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  902): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
,D/SurfaceControl(  902): Excessive delay in blankDisplay() while turning screen off: 374ms
V/KeyguardServiceDelegate(  902): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43406020)
D/NfcService( 1252): ScreenObserver: OFF
,D/NfcService( 1252): applyRouting - 0
D/PMS     (  902): nativeSetInteractive:false
D/PMS     (  902): nativeSetInteractive:false done
D/PMS     (  902): nativeSetAutoSuspend:true
D/PMS     (  902): nativeSetAutoSuspend:true done
D/HABCtrl (  902): TPE algorithm. remove timeout.
D/PMS     (  902): OOBE c monitor 11
I/InputMethodManagerService(  902): screenObserver, isScreenOn=false
D/PMN     (  902): wakingUp
I/InputMethodManagerService(  902): Disable input method client, pid=4401
D/PMS     (  902): acquireWL(43432520): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
,V/KeyguardServiceDelegate(  902): **** SHOWN CALLED ****
,D/NfcService( 1252): applyRouting -2
I/WindowManager(  902): No lock screen! windowToken=null
D/PMN     (  902): onScreenOn
D/PMS     (  902): releaseWL(43432520): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/InputManager(  902): Cancel all due to getting PMS screen off broadcast
,D/WirelessDisplayService(  902): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  902): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  902): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1112): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/MtpService( 2424): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1252): applyRouting - 0
,D/NfcService( 1252): applyRouting -2
D/MtpService( 2424): [MTP][onReceive]-
,D/AutoSetting( 1398): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  902): acquireWL(424543c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  902): n_update end
D/PMS     (  902): releaseWL(424543c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  902): acquireWL(432c7670): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
D/PMS     (  902): releaseWL(432c7670): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  902): updateBatteryInfo
,D/AutoSetting( 1398): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,V/NotificationService(  902): batLight: Full, plugged
V/LightsService(  902): setLight #8: color=#c8c800
D/qdlights(  902): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  902): setLight #8: color=#c800
D/qdlights(  902): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  902): [LedInfo] has indicator attribute
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/WirelessDisplayService(  902): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  902): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  902): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  902): << updateStatus
,D/WifiDataStallTracker(  902): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  902): startDataStallAlarm: tag=19386 delay=15s
D/TetherSettings( 4177): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4177): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4177): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4177): Cust_ConnectToPC   : spcsc>false
D/        ( 4177): Cust_ConnectToPC   : IPT>true
,D/        ( 4177): Cust_ConnectToPC   : Singel_USB>false
D/WifiNative-wlan0(  902): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): SET_SCREEN_ON:On
I/wpa_supplicant( 1161): htc_wext_set_keepalive +
I/wpa_supplicant( 1161): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1161): getPrivFuncNum +	
I/wpa_supplicant( 1161): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1161): htc_wext_set_keepalive fnum = 0x8bf6
W/Settings( 4177): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/wpa_supplicant( 1161): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1161): BG scan when screen On
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): Match BG scan, scan!
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  902):    returned true
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/libc    (  902): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-,err=8
D/libc    (  902): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  902): [NET] getaddrinfo-, 1
D/libc    (  902): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =c5a3 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
E/SmartNS_Utility( 4177): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4177): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4177): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AlarmManager(  902): ACTION_SCREEN_ON
I/AlarmManager(  902): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  902): [AlarmQueuing] done recovering
I/AlarmManager(  902): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  902): [AlarmQueuing] done EPS screen off alarm recovering
W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
D/WIFI_ICON( 1112): WifiActivity: 2
,I/PSReceiver( 4177): onReceive:android.intent.action.USER_PRESENT
,I/ClockThread( 1112): stop update clock
,I/SmartNS_PSService( 4177): onReceive:android.intent.action.USER_PRESENT
,V/SRS_Proc(  371): ParamSet string: screen_state=on
W/Settings( 4177): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4177):  defaultType:0
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
W/ContextImpl( 4177): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/NotificationService(  902): batLight: Full, plugged
V/LightsService(  902): setLight #8: color=#c8c800
D/qdlights(  902): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  902): setLight #8: color=#c800
D/qdlights(  902): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,D/WirelessDisplayService(  902): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/PMS     (  902): releaseWL(43173c80): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
D/NetworkPolicy(  902): updateScreenOn: false
,I/ActivityManager(  902): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4655 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/ContextImpl( 4655): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/SmartSyncUtils( 4655): isEpsOn(), nState = 0
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1810): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1810): onScreenOn: 1452525662180
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1810): onScreenOn: 1452525662180
D/PMS     (  902): acquireWL(42ec2140): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1435 10028 null
D/PMS     (  902): acquireWL(43547f28): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4655 1000 null
D/PMS     (  902): releaseWL(42ec2140): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  902): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421548b0
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  902): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 2
W/SensorService(  902): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  902): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  902): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421548b0, eanble = 0, strlen(mName) = 91
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  902): Listener[0] = com.htc.smartdim.sensor_eye@4260efc0
,W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  902): goingToSleep
D/PMS     (  902): acquireWL(42548fa8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 902 1000 null
,D/PMS     (  902): releaseWL(43547f28): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/AlarmManager(  902): ACTION_SCREEN_OFF
I/AlarmManager(  902): [AlarmQueuing] screen off now: 
I/AlarmManager(  902): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  902): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  902): stopDataStallAlarm: current tag=19386 mDataStallAlarmIntent=PendingIntent{43a13e30: PendingIntentRecord{4252a750 android broadcastIntent}}
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 192
,D/WifiStateMachine(  902): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
D/SmartSyncUtils( 4655): getMobilePolicyEnabled, result = true
D/WifiNative-wlan0(  902): doBoolean: SignalStrength 97
,I/AlarmManager(  902): [AlarmQueuing] wifi connection: true
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  902):    returned true
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WifiNative-wlan0(  902): doBoolean: SET_SCREEN_ON 0
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [2][0][0]
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): SET_SCREEN_ON:Off
I/wpa_supplicant( 1161): htc_wext_set_keepalive +
I/wpa_supplicant( 1161): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1161): getPrivFuncNum +	
I/wpa_supplicant( 1161): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1161): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiNative-wlan0(  902): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 1161): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1161): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1161): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  902):    returned true
D/Process (  902): killProcessQuiet, pid=4290
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WIFI_ICON( 1112): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
D/PMS     (  902): acquireWL(43fc1cc8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 902 1000 null
I/ActivityManager(  902): Killing 4290:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  902):    returned true
,V/SRS_Proc(  371): ParamSet string: screen_state=off
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  902): releaseWL(43fc1cc8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
I/ActivityManager(  902): Recipient 4290
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1241): start background delete task...
,D/NetworkPolicy(  902): updateScreenOn: false
D/ContactMessageStore( 1241): size: 0 , 0
D/ContactMessageStore( 1241): Background delete complete
D/WifiNative-wlan0(  902): doString: SIGNAL_POLL
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/SmartSyncUtils( 4655): isEpsOn(), nState = 0
,W/ContextImpl( 4655): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4655): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4655): isEpsOn(), nState = 0
I/SensorManager(  902): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4260efc0
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  902): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 1
W/SensorService(  902): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  902): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4260efc0, eanble = 0, strlen(mName) = 36
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  902): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 0
W/SensorService(  902): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4260efc0, eanble = 0, strlen(mName) = 36
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WifiService(  902): New client listening to asynchronous messages
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  902): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4260efc0
E/ActivityThread(  902): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4255acf8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  902): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4255acf8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  902): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  902): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  902): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  902): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  902): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  902): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  902): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  902): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  902): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  902): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  902): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  902): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  902): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  902): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  902): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  902): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  902): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  902): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  902): 	at dalvik.system.NativeStart.main(Native Method)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  902): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  902): Find DNS Address www.htc.com/104.81.130.175
,D/AutoSetting( 1398): service - mHandler: cancel location update
,D/AutoSetting( 1398): service -           changes count: 0
,D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] getTotalRam: 1873 Mb
D/PMS     (  902): acquireWL(42bd70c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1435 10028 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1810): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1810): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1810): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1810): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1810): onScreenOff
D/PMS     (  902): releaseWL(42bd70c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/ActivityManager(  902): Activity pause timeout for ActivityRecord{41ca6ff8 u0 com.test.thalitest/.MainActivity t2}
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,I/GAV2    ( 4539): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  902): acquireWL(42454b40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1435 10028 null
,D/PMS     (  902): acquireWL(42d083a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1435 10028 null
,D/PMS     (  902): releaseWL(42454b40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  902): releaseWL(42d083a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/jxcore-log( 4401): Test app app.js loaded
I/jxcore-log( 4401): 
,I/Choreographer( 4401): Skipped 529 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4401): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4401): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41aa3420 VFEDH.C. .F....ID 0,0-720,1134 #64}
,D/PMS     (  902): releaseWL(42548fa8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
I/chromium( 4401): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-73
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=13 entropy=0
D/wpa_supplicant( 1161): Add randomness: count=14 entropy=1
D/wpa_supplicant( 1161): Add randomness: count=15 entropy=2
D/wpa_supplicant( 1161): Add randomness: count=16 entropy=3
D/wpa_supplicant( 1161): Add randomness: count=17 entropy=4
D/wpa_supplicant( 1161): Add randomness: count=18 entropy=5
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplica,nt( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-73
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=19 entropy=6
D/wpa_supplicant( 1161): Add randomness: count=20 entropy=7
D/wpa_supplicant( 1161): Add randomness: count=21 entropy=8
D/wpa_supplicant( 1161): Add randomness: count=22 entropy=9
D/wpa_supplicant( 1161): Add randomness: count=23 entropy=10
D/wpa_supplicant( 1161): Add randomness: count=24 entropy=11
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
,I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1161): State: DISCONNECTED -> INACTIVE
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  902): doString: LIST_DONGLES
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  902): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/HTCRequest(  902): WifiMonitor:handleSupplicantStateChange(): SSID
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiMonitor(  902): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,D/WifiP2pService(  902): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  902): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (779) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-47
I/wpa_supplicant( 1161): tsf=0000000113631756
,I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-56
I/wpa_supplicant( 1161): tsf=0000000113631792
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2452
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000113631802
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=3
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-55
I/wpa_supplicant( 1161): tsf=0000000106751236
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-85
I/wpa_supplicant( 1161): tsf=0000000113631811
I/wpa_supplicant( 1161): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=5
I/wpa_supplicant( 1161): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-84
I/wpa_supplicant( 1161): tsf=0000000113631821
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC5999698
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  902): getDiscoveryDongleList
,D/WifiStateMachine(  902): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  902): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43729f48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@43729f48 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  902): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@43729f48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  902): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 113631756, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/WifiStateMachine(  902): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 113631792, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2452, timestamp: 113631802, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  902): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 106751236, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 113631811, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 113631821, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): add 6 to mScanResults
,V/ScoreHelper(  902): Only print Top 10 in ApScanList
,V/ScoreHelper(  902):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  902):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  77, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  902):  + computeScore(NG700): 1
,D/WifiStateMachine(  902): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  902): == begin of scan result ==
,D/WifiStateMachine(  902): == (6) end of scan result ==
,D/WifiNotificationController(  902): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  902): getDiscoveryDongleList,
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,D/Process (  902): killProcessQuiet, pid=4313
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 4313:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 4313
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/Process (  902): killProcessQuiet, pid=4330
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 4330:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 4330
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 10.967MB for 24676-byte allocation
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 11.015MB for 55510-byte allocation
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 11.032MB for 54548-byte allocation
D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 11.108MB for 82844-byte allocation
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 11.115MB for 55788-byte allocation
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 11.155MB for 72358-byte allocation
,D/libc    ( 4472): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4472): [NET] getaddrinfo-,err=8
D/libc    ( 4472): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4472): [NET] getaddrinfo-, 1
,D/libc    ( 4472): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =4943 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 27
D/libc    (  364): [NET]res_nsend:resplen=93
D/libc    (  364): [NET]res_queryN: exit 3, ancount=3
,D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4472): [NET] getaddrinfo_proxy-, success
I/global  ( 4472): call createSocket() return a new socket.
D/libc    ( 4472): [NET] getaddrinfo+,hn 11(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4472): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4472): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4472): [NET] getaddrinfo-,err=8
,D/PMS     (  902): acquireWL(43faa650): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4472 10026 null,
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.facebook.katana (4472/10026)
,D/CaptivePortalTracker(  902): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  902): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  902): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/global  ( 4472): I/O error closing connection
I/global  ( 4472): java.net.SocketException: Socket is closed
I/global  ( 4472): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4472): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4472): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4472): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4472): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4472): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4472): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4472): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4472): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4472): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4472): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4472): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4472): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4472): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4472): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4472): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4472): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4472): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4472): Removing a connection that never existed!
D/PMS     (  902): releaseWL(43faa650): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  902): acquireWL(43f75a30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(43f75a30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  902): updateBatteryInfo
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-73
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=25 entropy=12
D/wpa_supplicant( 1161): Add randomness: count=26 entropy=13
D/wpa_supplicant( 1161): Add randomness: count=27 entropy=14
D/wpa_supplicant( 1161): Add randomness: count=28 entropy=15
D/wpa_supplicant( 1161): Add randomness: count=29 entropy=16
D/wpa_supplicant( 1161): Add randomness: count=30 entropy=17
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,D/wpa_supplicant( 1161): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
,D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-73
,I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=31 entropy=18
,D/WifiNative-wlan0(  902): doString: LIST_DONGLES
D/wpa_supplicant( 1161): Add randomness: count=32 entropy=19
D/wpa_supplicant( 1161): Add randomness: count=33 entropy=20
D/wpa_supplicant( 1161): Add randomness: count=34 entropy=21
D/wpa_supplicant( 1161): Add randomness: count=35 entropy=22
D/wpa_supplicant( 1161): Add randomness: count=36 entropy=23
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  902): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  902): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (779) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-47
I/wpa_supplicant( 1161): tsf=0000000131883538
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-56
I/wpa_supplicant( 1161): tsf=0000000131883576
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2452
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000131883586
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=3
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-55
I/wpa_supplicant( 1161): tsf=0000000106751236
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
,I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-85
I/wpa_supplicant( 1161): tsf=0000000131883607
I/wpa_supplicant( 1161): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=5
I/wpa_supplicant( 1161): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-84
I/wpa_supplicant( 1161): tsf=0000000131883596
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC5999698
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  902): getDiscoveryDongleList
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/WifiStateMachine(  902): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 131883538, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  902): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 131883576, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2452, timestamp: 131883586, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  902): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  902): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 106751236, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 131883607, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 131883596, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  902): add 6 to mScanResults,
V/ScoreHelper(  902): Only print Top 10 in ApScanList
V/ScoreHelper(  902):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  902):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  77, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  902):  + computeScore(NG700): 1
D/WifiStateMachine(  902): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  902): == begin of scan result ==
D/WifiStateMachine(  902): == (6) end of scan result ==
D/WifiNotificationController(  902): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/WirelessDisplayService(  902): getDiscoveryDongleList
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1398): service - mHandler: update timezone
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1519): service - onCreate()
W/ActivityManager(  902): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  902): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1588): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1588): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  902): batLight: Full, plugged
V/LightsService(  902): setLight #8: color=#c8c800
D/qdlights(  902): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  902): setLight #8: color=#c800
D/qdlights(  902): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  902): [LedInfo] has indicator attribute
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  902): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1519): service - mHandler: update timezone
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1519): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1519): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1588): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
I/PhoneStatusBar( 1112): removeNotification.gc:57
,D/DotMatrix( 1588): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1112): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41be7078 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.htc.htclocationservice 2 8 2 11
,D/AutoSetting( 1398): service - handleMessage() stop self
D/PMS     (  902): acquireWL(4237a7a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10028}
V/AlarmManager(  902): sending alarm PendingIntent{41c9f1f0: PendingIntentRecord{422ff408 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140854, Int=0
V/AlarmManager(  902): sending alarm PendingIntent{4247e638: PendingIntentRecord{422ec8c8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140921, Int=0
,D/GpsLocationProvider(  902): ALARM_XTRA_TIMEOUT
D/PMS     (  902): acquireWL(422bbf78): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 902 1000 null
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1362/10028)
D/PMS     (  902): releaseWL(4237a7a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  902): acquireWL(41d94528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
,D/AutoSetting( 1398): service - handleMessage() quit looper
,D/AutoSetting( 1398): service - onDestroy() END
D/PMS     (  902): releaseWL(41d94528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GpsLocationProvider(  902): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  902): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/libc    (  902): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  902): [NET] getaddrinfo-,err=8
D/libc    (  902): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  902): [NET] getaddrinfo-, 1
,D/libc    (  902): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =63e9 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=243
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  902): [NET] getaddrinfo_proxy-, success
I/global  (  902): call createSocket() return a new socket.
D/libc    (  902): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  902): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  902): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  902): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  902): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  902):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  902): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  902): releaseWL(422bbf78): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
,I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/Process (  902): killProcessQuiet, pid=3882
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3882:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3882
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-73
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1161): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-91
D/wpa_supplicant( 1161): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=37 entropy=24
D/wpa_supplicant( 1161): Add randomness: count=38 entropy=25
D/wpa_supplicant( 1161): Add randomness: count=39 entropy=26
D/wpa_supplicant( 1161): Add randomness: count=40 entropy=27
D/wpa_supplicant( 1161): Add randomness: count=41 entropy=28
D/wpa_supplicant( 1161): Add randomness: count=42 entropy=29
D/wpa_supplicant( 1161): Add randomness: count=43 entropy=30
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_s,upplicant( 1161): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 6: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
D/WifiNative-wlan0(  902): doString: LIST_DONGLES
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-73
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1161): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-91
D/wpa_supplicant( 1161): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=44 entropy=31
D/wpa_supplicant( 1161): Add randomness: count=45 entropy=32
D/wpa_supplicant( 1161): Add randomness: count=46 entropy=33
D/wpa_supplicant( 1161): Add randomness: count=47 entropy=34
D/wpa_supplicant( 1161): Add randomness: count=48 entropy=35
D/wpa_supplicant( 1161): Add randomness: count=49 entropy=36
D/wpa_supplicant( 1161): Add randomness: count=50 entropy=37
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1161): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIV,E
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  902): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
,I/wpa_supplicant( 1161): reply (924) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-47
I/wpa_supplicant( 1161): tsf=0000000150143382
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-56
I/wpa_supplicant( 1161): tsf=0000000150143425
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2452
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000131883586
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=3
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-55
I/wpa_supplicant( 1161): tsf=0000000106751236
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-84
I/wpa_supplicant( 1161): tsf=0000000150143445
I/wpa_supplicant( 1161): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=5
I/wpa_supplicant( 1161): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-85
I/wpa_supplicant( 1161): tsf=0000000150143455
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC5999698
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=6
I/wpa_supplicant( 1161): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-91
I/wpa_supplicant( 1161): tsf=0000000150143465
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1161): ####
D/WifiStateMachine(  902): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 150143382, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 150143425, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2452, timestamp: 131883586, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 106751236, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  902): InactiveState{ when=-10ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  902): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 150143445, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  902): P2pEnabledState{ when=-12ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  902): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 150143455, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  902): DefaultState{ when=-12ms what=147461 target=com.android.internal.util.StateMachine$,SmHandler }
D/WirelessDisplayService(  902): getDiscoveryDongleList
,D/WifiStateMachine(  902): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,D/WifiStateMachine(  902): 6: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -91, frequency: 2437, timestamp: 150143465, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): add 7 to mScanResults
,V/ScoreHelper(  902): Only print Top 10 in ApScanList
,V/ScoreHelper(  902):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  902):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  69, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  902):  + computeScore(NG700): 1
,D/WifiStateMachine(  902): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  902): == begin of scan result ==
,D/WifiStateMachine(  902): == (7) end of scan result ==
,D/WirelessDisplayService(  902): getDiscoveryDongleList
D/WifiNotificationController(  902): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,I/ActivityManager(  902): Waited long enough for: ServiceRecord{43ef0dd0 u0 com.htc.htclocationservice/.AutoSettingService}
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-73
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1161): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-90
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=51 entropy=38
D/wpa_supplicant( 1161): Add randomness: count=52 entropy=39
D/wpa_supplicant( 1161): Add randomness: count=53 entropy=40
D/wpa_supplicant( 1161): Add randomness: count=54 entropy=41
D/wpa_supplicant( 1161): Add randomness: count=55 entropy=42
D/wpa_supplicant( 1161): Add randomness: count=56 entropy=43
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 5: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 se,ries' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-73
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1161): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-90
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=57 entropy=44
D/wpa_supplicant( 1161): Add randomness: count=58 entropy=45
D/wpa_supplicant( 1161): Add randomness: count=59 entropy=46
D/wpa_supplicant( 1161): Add randomness: count=60 entropy=47
D/wpa_supplicant( 1161): Add randomness: count=61 entropy=48
D/wpa_supplicant( 1161): Add randomness: count=62 entropy=49
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE,
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  902): doString: LIST_DONGLES
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  902): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  902): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
,I/wpa_supplicant( 1161): reply (924) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-47
I/wpa_supplicant( 1161): tsf=0000000168312164
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-56
,I/wpa_supplicant( 1161): tsf=0000000168312190
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2452
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000168312201
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=3
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-55
I/wpa_supplicant( 1161): tsf=0000000106751236
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-84
I/wpa_supplicant( 1161): tsf=0000000168312211
I/wpa_supplicant( 1161): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=5
I/wpa_supplicant( 1161): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-85
I/wpa_supplicant( 1161): tsf=0000000168312221
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC5999698
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=6
I/wpa_supplicant( 1161): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-90
I/wpa_supplicant( 1161): tsf=0000000168312231
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  902): getDiscoveryDongleList
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,D/WifiStateMachine(  902): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 168312164, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 168312190, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2452, timestamp: 168312201, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  902): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 106751236, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 168312211, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  902): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 168312221, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 6: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -90, frequency: 2437, timestamp: 168312231, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  902): add 7 to mScanResults
V/ScoreHelper(  902): Only print Top 10 in ApScanList
,V/ScoreHelper(  902):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  902):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  69, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  902):  + computeScore(NG700): 1
D/WifiStateMachine(  902): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  902): == begin of scan result ==
,D/WifiStateMachine(  902): == (7) end of scan result ==
D/WifiNotificationController(  902): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,D/WirelessDisplayService(  902): getDiscoveryDongleList
,D/PMS     (  902): acquireWL(425da4b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{42089898: PendingIntentRecord{42326528 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=168548, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(425da4b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/Process (  902): killProcessQuiet, pid=4277
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 4277:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 4277
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  902): acquireWL(423d3240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(423d3240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  902): updateBatteryInfo
,D/PowerUI ( 1112): closing low battery warning: level=100
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1161): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-90
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=63 entropy=50
D/wpa_supplicant( 1161): Add randomness: count=64 entropy=51
D/wpa_supplicant( 1161): Add randomness: count=65 entropy=52
D/wpa_supplicant( 1161): Add randomness: count=66 entropy=53
D/wpa_supplicant( 1161): Add randomness: count=67 entropy=54
D/wpa_supplicant( 1161): Add randomness: count=68 entropy=55
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 5: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 se,ries' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-78
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1161): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-90
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=69 entropy=56
D/wpa_supplicant( 1161): Add randomness: count=70 entropy=57
D/wpa_supplicant( 1161): Add randomness: count=71 entropy=58
D/wpa_supplicant( 1161): Add randomness: count=72 entropy=59
D/wpa_supplicant( 1161): Add randomness: count=73 entropy=60
D/wpa_supplicant( 1161): Add randomness: count=74 entropy=61
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiP2pService(  902): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  902): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  902): doString: LIST_DONGLES
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  902): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1161): reply (811) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-47
I/wpa_supplicant( 1161): tsf=0000000186633638
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-56
I/wpa_supplicant( 1161): tsf=0000000186633665
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2452
I/wpa_supplicant( 1161): level=-78,
I/wpa_supplicant( 1161): tsf=0000000186633676
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-84
I/wpa_supplicant( 1161): tsf=0000000186633686
I/wpa_supplicant( 1161): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=5
I/wpa_supplicant( 1161): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-85
I/wpa_supplicant( 1161): tsf=0000000186633696
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC5999698
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=6
I/wpa_supplicant( 1161): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-90
I/wpa_supplicant( 1161): tsf=0000000186633706
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  902): getDiscoveryDongleList
D/WifiStateMachine(  902): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 186633638, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/WifiStateMachine(  902): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 186633665, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2452, timestamp: 186633676, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  902): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 186633686, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 186633696, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 5: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -90, frequency: 2437, timestamp: 186633706, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  902): add 6 to mScanResults
D/WifiStateMachine(  902): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  902): Only print Top 10 in ApScanList
,V/ScoreHelper(  902):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  902):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  69, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  902):  + computeScore(NG700): 1
D/WifiStateMachine(  902): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  902): == begin of scan result ==
,D/WifiStateMachine(  902): == (6) end of scan result ==
D/WifiNotificationController(  902): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  902): getDiscoveryDongleList
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,D/PMS     (  902): acquireWL(42302fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
,D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): closing low battery warning: level=100
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  902): updateBatteryInfo
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
,I/HtcPowerSaver(  902): >> updateStatus
,D/PMS     (  902): releaseWL(42302fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-74
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=75 entropy=62
D/wpa_supplicant( 1161): Add randomness: count=76 entropy=63
D/wpa_supplicant( 1161): Add randomness: count=77 entropy=64
D/wpa_supplicant( 1161): Add randomness: count=78 entropy=65
D/wpa_supplicant( 1161): Add randomness: count=79 entropy=66
D/wpa_supplicant( 1161): Add randomness: count=80 entropy=67
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,D/wpa_supplicant( 1161): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
,I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-74
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
,D/wpa_supplicant( 1161): Add randomness: count=81 entropy=68
D/wpa_supplicant( 1161): Add randomness: count=82 entropy=69
D/wpa_supplicant( 1161): Add randomness: count=83 entropy=70
D/wpa_supplicant( 1161): Add randomness: count=84 entropy=71
D/wpa_supplicant( 1161): Add randomness: count=85 entropy=72
D/wpa_supplicant( 1161): Add randomness: count=86 entropy=73
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  902): doString: LIST_DONGLES
,W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  902): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  902): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1161): reply (924) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-47
I/wpa_supplicant( 1161): tsf=0000000204863353
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-56
I/wpa_supplicant( 1161): tsf=0000000204863391
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
,I/wpa_supplicant( 1161): freq=2452
I/wpa_supplicant( 1161): level=-74
I/wpa_supplicant( 1161): tsf=0000000204863402
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-84
I/wpa_supplicant( 1161): tsf=0000000186633686
I/wpa_supplicant( 1161): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=5
I/wpa_supplicant( 1161): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-85
I/wpa_supplicant( 1161): tsf=0000000204863421
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC5999698
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=6
I/wpa_supplicant( 1161): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-90
I/wpa_supplicant( 1161): tsf=0000000186633706
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1161): ====,
I/wpa_supplicant( 1161): id=7
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000204863379
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  902): getDiscoveryDongleList
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/WifiStateMachine(  902): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 204863353, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 204863391, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  902): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  902): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2452, timestamp: 204863402, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 186633686, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 204863421, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 5: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -90, frequency: 2437, timestamp: 186633706, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 204863379, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  902): add 7 to mScanResults
,V/ScoreHelper(  902): Only print Top 10 in ApScanList
V/ScoreHelper(  902):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  902):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  69, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  902):  + computeScore(NG700): 1
D/WifiStateMachine(  902): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  902): == begin of scan result ==
,D/WifiStateMachine(  902): == (7) end of scan result ==
,D/WirelessDisplayService(  902): getDiscoveryDongleList
D/WifiNotificationController(  902): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-74
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=87 entropy=74
D/wpa_supplicant( 1161): Add randomness: count=88 entropy=75
D/wpa_supplicant( 1161): Add randomness: count=89 entropy=76
D/wpa_supplicant( 1161): Add randomness: count=90 entropy=77
D/wpa_supplicant( 1161): Add randomness: count=91 entropy=78
D/wpa_supplicant( 1161): Add randomness: count=92 entropy=79
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable netwo,rk found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-74
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=93 entropy=80
D/wpa_supplicant( 1161): Add randomness: count=94 entropy=81
D/wpa_supplicant( 1161): Add randomness: count=95 entropy=82
D/wpa_supplicant( 1161): Add randomness: count=96 entropy=83
D/wpa_supplicant( 1161): Add randomness: count=97 entropy=84
D/wpa_supplicant( 1161): Add randomness: count=98 entropy=85
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  902): doString: LIST_DONGLES
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  902): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (779) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-47
I/wpa_supplicant( 1161): tsf=0000000223113463
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-56
I/wpa_supplicant( 1161): tsf=0000000223113501
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2452
I/wpa_supplicant( 1161): level=-74
I/wpa_supplicant( 1161): tsf=0000000223113511
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-84
I/wpa_supplicant( 1161): tsf=0000000186633686
I/wpa_supplicant( 1161): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=5
I/wpa_supplicant( 1161): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-84
I/wpa_supplicant( 1161): tsf=0000000223113531
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC5999698
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=7
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-56
I/wpa_supplicant( 1161): tsf=0000000223113490
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WifiP2pService(  902): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  902): getDiscoveryDongleList
,D/WifiStateMachine(  902): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  902): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 223113463, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/WifiStateMachine(  902): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 223113501, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2452, timestamp: 223113511, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 186633686, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 223113531, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 223113490, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): add 6 to mScanResults
,V/ScoreHelper(  902): Only print Top 10 in ApScanList
,V/ScoreHelper(  902):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  902):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  77, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  77, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  902):  + computeScore(NG700): 1
,D/WifiStateMachine(  902): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  902): == begin of scan result ==
,D/WifiStateMachine(  902): == (6) end of scan result ==
D/WifiNotificationController(  902): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/WirelessDisplayService(  902): getDiscoveryDongleList
,D/PMS     (  902): acquireWL(43eed2d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10026}
,V/AlarmManager(  902): sending alarm PendingIntent{4304fc90: PendingIntentRecord{437b8148 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=227745, Int=0
,I/ActivityManager(  902): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4695 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  902): sending alarm PendingIntent{424a6030: PendingIntentRecord{424ca480 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452525771524, Int=10800000
,D/PMS     (  902): releaseWL(43eed2d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.aurora (4695/10047)
,D/Process (  902): killProcessQuiet, pid=4348
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 4348:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 4348
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  902): acquireWL(43f7c6c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{42089898: PendingIntentRecord{42326528 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=228548, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(43f7c6c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/PMS     (  902): acquireWL(425a4c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{10026}
,V/AlarmManager(  902): sending alarm PendingIntent{4326d5c8: PendingIntentRecord{437b8148 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=230752, Int=0
,D/PMS     (  902): releaseWL(425a4c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-73
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=99 entropy=86
D/wpa_supplicant( 1161): Add randomness: count=100 entropy=87
D/wpa_supplicant( 1161): Add randomness: count=101 entropy=88
D/wpa_supplicant( 1161): Add randomness: count=102 entropy=89
D/wpa_supplicant( 1161): Add randomness: count=103 entropy=90
D/wpa_supplicant( 1161): Add randomness: count=104 entropy=91
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable ,network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-73
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=105 entropy=92
D/wpa_supplicant( 1161): Add randomness: count=106 entropy=93
D/wpa_supplicant( 1161): Add randomness: count=107 entropy=94
D/wpa_supplicant( 1161): Add randomness: count=108 entropy=95
D/wpa_supplicant( 1161): Add randomness: count=109 entropy=96
D/wpa_supplicant( 1161): Add randomness: count=110 entropy=97
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  902): doString: LIST_DONGLES
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  902): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (779) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-47
I/wpa_supplicant( 1161): tsf=0000000241393287
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-56
I/wpa_supplicant( 1161): tsf=0000000241393315
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2452
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000241393337
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-84
I/wpa_supplicant( 1161): tsf=0000000241393347
I/wpa_supplicant( 1161): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=5
I/wpa_supplicant( 1161): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-85
I/wpa_supplicant( 1161): tsf=0000000241393357
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC5999698
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=7
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-56
I/wpa_supplicant( 1161): tsf=0000000241393326
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WifiP2pService(  902): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  902): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 241393287, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  902): getDiscoveryDongleList
,D/WifiStateMachine(  902): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,D/WifiStateMachine(  902): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 241393315, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2452, timestamp: 241393337, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 241393347, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 241393357, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 241393326, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): add 6 to mScanResults
,V/ScoreHelper(  902): Only print Top 10 in ApScanList
,V/ScoreHelper(  902):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  902):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  77, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  902):  + computeScore(NG700): 1
,D/WifiStateMachine(  902): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  902): == begin of scan result ==
,D/WifiStateMachine(  902): == (6) end of scan result ==
,D/WirelessDisplayService(  902): getDiscoveryDongleList,
D/WifiNotificationController(  902): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  902): acquireWL(4342fc28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/UsbnetService(  902): BroadcastReceiver::onReceive+
D/UsbnetService(  902): onReceive BATTERY_CHANGED
D/UsbnetService(  902):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  902): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  902): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PMS     (  902): releaseWL(4342fc28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1588): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1588): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  902): runPSCheck
D/HtcPowerSaver(  902): Checking...
I/HtcPowerSaver(  902): >> updateStatus
,I/HtcPowerSaver(  902): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  902): << updateStatus
,W/AppWidgetServiceImpl(  902): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-73
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=111 entropy=98
D/wpa_supplicant( 1161): Add randomness: count=112 entropy=99
D/wpa_supplicant( 1161): Add randomness: count=113 entropy=100
D/wpa_supplicant( 1161): Add randomness: count=114 entropy=101
D/wpa_supplicant( 1161): Add randomness: count=115 entropy=102
D/wpa_supplicant( 1161): Add randomness: count=116 entropy=103
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suit,able network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-73
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1161): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=117 entropy=104
D/WifiNative-wlan0(  902): doString: LIST_DONGLES
D/wpa_supplicant( 1161): Add randomness: count=118 entropy=105
D/wpa_supplicant( 1161): Add randomness: count=119 entropy=106
D/wpa_supplicant( 1161): Add randomness: count=120 entropy=107
D/wpa_supplicant( 1161): Add randomness: count=121 entropy=108
D/wpa_supplicant( 1161): Add randomness: count=122 entropy=109
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  902): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  902): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161),: WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (779) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-47
I/wpa_supplicant( 1161): tsf=0000000241393287
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-56
I/wpa_supplicant( 1161): tsf=0000000259643152
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2452
I/wpa_supplicant( 1161): level=-73
I/wpa_supplicant( 1161): tsf=0000000259643175
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-84
I/wpa_supplicant( 1161): tsf=0000000259643185
I/wpa_supplicant( 1161): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=5
I/wpa_supplicant( 1161): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-85
I/wpa_supplicant( 1161): tsf=0000000259643196
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC5999698
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=7
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-56
I/wpa_supplicant( 1161): tsf=0000000259643165
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  902): getDiscoveryDongleList
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/WifiStateMachine(  902): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 241393287, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 259643152, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2452, timestamp: 259643175, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 259643185, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 259643196, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  902): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  902): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 259643165, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): add 6 to mScanResults
,V/ScoreHelper(  902): Only print Top 10 in ApScanList
,V/ScoreHelper(  902):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  902):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  77, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  902):  + computeScore(NG700): 1
,D/WifiStateMachine(  902): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  902): == begin of scan result ==
,D/WifiStateMachine(  902): == (6) end of scan result ==
,D/WirelessDisplayService(  902): getDiscoveryDongleList
D/WifiNotificationController(  902): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-74
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-83
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=123 entropy=110
D/wpa_supplicant( 1161): Add randomness: count=124 entropy=111
D/wpa_supplicant( 1161): Add randomness: count=125 entropy=112
D/wpa_supplicant( 1161): Add randomness: count=126 entropy=113
D/wpa_supplicant( 1161): Add randomness: count=127 entropy=114
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,D/wpa_supplicant( 1161): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-74
,I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-83
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=128 entropy=115
D/wpa_supplicant( 1161): Add randomness: count=129 entropy=116
D/wpa_supplicant( 1161): Add randomness: count=130 entropy=117
D/wpa_supplicant( 1161): Add randomness: count=131 entropy=118
D/wpa_supplicant( 1161): Add randomness: count=132 entropy=119
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  902): doString: LIST_DONGLES
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  902): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  902): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (779) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-47
I/wpa_supplicant( 1161): tsf=0000000277873629
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-56
I/wpa_supplicant( 1161): tsf=0000000277873656
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2452
I/wpa_supplicant( 1161): level=-74
I/wpa_supplicant( 1161): tsf=0000000277873668
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-83
I/wpa_supplicant( 1161): tsf=0000000259643185
I/wpa_supplicant( 1161): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=5
I/wpa_supplicant( 1161): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
,I/wpa_supplicant( 1161): level=-85
I/wpa_supplicant( 1161): tsf=0000000277873687
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC5999698
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=7
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-56
I/wpa_supplicant( 1161): tsf=0000000259643165
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WifiP2pService(  902): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  902): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 277873629, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  902): getDiscoveryDongleList
,D/WifiStateMachine(  902): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  902): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 277873656, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,D/WifiStateMachine(  902): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2452, timestamp: 277873668, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -83, frequency: 2437, timestamp: 259643185, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 277873687, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 259643165, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  902): add 6 to mScanResults
,V/ScoreHelper(  902): Only print Top 10 in ApScanList
V/ScoreHelper(  902):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  902):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  77, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-83], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  902):  + computeScore(NG700): 1
D/WifiStateMachine(  902): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  902): == begin of scan result ==
,D/WifiStateMachine(  902): == (6) end of scan result ==
,D/WirelessDisplayService(  902): getDiscoveryDongleList,
D/WifiNotificationController(  902): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,D/PMS     (  902): acquireWL(435530b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 902 1000 WorkSource{1000}
,V/AlarmManager(  902): sending alarm PendingIntent{42089898: PendingIntentRecord{42326528 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=288548, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  902): releaseWL(435530b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  902): acquireWL(43d70dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(43d70dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-74
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-83
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=133 entropy=120
D/wpa_supplicant( 1161): Add randomness: count=134 entropy=121
D/wpa_supplicant( 1161): Add randomness: count=135 entropy=122
D/wpa_supplicant( 1161): Add randomness: count=136 entropy=123
D/wpa_supplicant( 1161): Add randomness: count=137 entropy=124
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161):, nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-74
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-83
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=138 entropy=125
D/wpa_supplicant( 1161): Add randomness: count=139 entropy=126
D/wpa_supplicant( 1161): Add randomness: count=140 entropy=127
D/WifiNative-wlan0(  902): doString: LIST_DONGLES
D/wpa_supplicant( 1161): Add randomness: count=141 entropy=128
D/wpa_supplicant( 1161): Add randomness: count=142 entropy=129
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  902): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (666) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000296112707
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-56
I/wpa_supplicant( 1161): tsf=0000000296112734
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_,supplicant( 1161): freq=2452
I/wpa_supplicant( 1161): level=-74
I/wpa_supplicant( 1161): tsf=0000000296112746
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-83
I/wpa_supplicant( 1161): tsf=0000000259643185
I/wpa_supplicant( 1161): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=5
I/wpa_supplicant( 1161): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-85
I/wpa_supplicant( 1161): tsf=0000000296112766
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC5999698
I/wpa_supplicant( 1161): ####
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  902): getDiscoveryDongleList
,D/WifiStateMachine(  902): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiP2pService(  902): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  902): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 296112707, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  902): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  902): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 296112734, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/WifiStateMachine(  902): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2452, timestamp: 296112746, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -83, frequency: 2437, timestamp: 259643185, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 296112766, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): add 5 to mScanResults
,V/ScoreHelper(  902): Only print Top 10 in ApScanList
,V/ScoreHelper(  902):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  902):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  77, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-83], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  902):  + computeScore(NG700): 1
,D/WifiStateMachine(  902): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  902): == begin of scan result ==
,D/WifiStateMachine(  902): == (5) end of scan result ==
,D/WirelessDisplayService(  902): getDiscoveryDongleList
D/WifiNotificationController(  902): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  902): acquireWL(41da9228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  902): n_update end
,D/PMS     (  902): releaseWL(41da9228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-74
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=143 entropy=130
D/wpa_supplicant( 1161): Add randomness: count=144 entropy=131
D/wpa_supplicant( 1161): Add randomness: count=145 entropy=132
D/wpa_supplicant( 1161): Add randomness: count=146 entropy=133
D/wpa_supplicant( 1161): Add randomness: count=147 entropy=134
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161):, nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-74
I/wpa_supplicant( 1161): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1161): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-85
D/WifiStateMachine(  902): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1161): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=148 entropy=135
D/wpa_supplicant( 1161): Add randomness: count=149 entropy=136
D/wpa_supplicant( 1161): Add randomness: count=150 entropy=137
D/wpa_supplicant( 1161): Add randomness: count=151 entropy=138
D/WifiNative-wlan0(  902): doString: LIST_DONGLES
D/wpa_supplicant( 1161): Add randomness: count=152 entropy=139
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  902): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  902): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  902): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  902): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (666) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-48
I/wpa_supplicant( 1161): tsf=0000000314403098
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-56
I/wpa_supplicant( 1161): tsf=0000000314403200
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2452
I/wpa_supplicant( 1161): level=-74
I/wpa_supplicant( 1161): tsf=0000000314403212
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-84
I/wpa_supplicant( 1161): tsf=0000000314403222
I/wpa_supplicant( 1161): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=UPC Wi-Free
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=5
I/wpa_supplicant( 1161): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-85
I/wpa_supplicant( 1161): tsf=0000000314403232
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC5999698
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  902): getDiscoveryDongleList,
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/WifiStateMachine(  902): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 314403098, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  902): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  902): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 314403200, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2452, timestamp: 314403212, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 314403222, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -85, frequency: 2437, timestamp: 314403232, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  902): add 5 to mScanResults
V/ScoreHelper(  902): Only print Top 10 in ApScanList
,V/ScoreHelper(  902):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  902):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  902):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq: 10 [2452], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  77, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  902):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  902): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  902):  + computeScore(NG700): 1,
D/WifiStateMachine(  902): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  902): == begin of scan result ==
,D/WifiStateMachine(  902): == (5) end of scan result ==
D/WifiNotificationController(  902): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  902): getDiscoveryDongleList
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,I/jxcore-log( 4401): --= Surplus to requirements =--
I/jxcore-log( 4401): 
I/jxcore-log( 4401): ****TEST TOOK:  ms ****
I/jxcore-log( 4401): 
,I/jxcore-log( 4401): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4401): 
,E/cutils-trace( 4717): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4717): ====startRecUseTime====
D/htc.customization.log.level( 4717):  is 
,W/CustomizationLogLevel( 4717): Level value is invalid, use default level 2
,D/CustomizationManager( 4717):  Read ACC file spent 0.126 (s)
D/CIDMapFileReader( 4717): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4717): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4717): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4717): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4717): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4717): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4717): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4717): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4717): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4717): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4717): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4717): Parsing tag category name = system
,I/CustomizationCIDLoader( 4717): Parsing tag category name = application
I/CustomizationCIDLoader( 4717): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4717): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4717): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4717): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4717): Parsing tag category name = Settings
D/CustomizationManager( 4717):  Read CID file spent 0.181 (s)
,D/CustomizationManager( 4717):  All configurations done spent 0.182 (s),
,W/HtcNativeFlag( 4717): Fail to get flag string for type 'customer', use default value
,W/HtcNativeFlag( 4717): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4717): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4717): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  902): deletePackageAsUser: pkg=com.test.thalitest, pid=4717, uid=2000 user=0
,I/ActivityManager(  902): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
,D/Process (  902): killProcessQuiet, pid=4401
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,I/ActivityManager(  902): Killing 4401:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
,W/ActivityManager(  902): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  902):   Force finishing activity ActivityRecord{41ca6ff8 u0 com.test.thalitest/.MainActivity t2}
,E/JavaBinder(  902): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  902): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1205): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  902): Got RemoteException sending setActive(false) notification to pid 4401 uid 10348
W/PackageSettings(  902): Skipping PackageSetting{421ad768 com.example.hello/10356} due to missing metadata
,I/ActivityManager(  902): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
,I/dalvikvm-heap( 4154): Grow heap (frag case) to 15.196MB for 1821008-byte allocation
,I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
I/acms    ( 1895): Unregistering com.test.thalitest
,E/acms    ( 1895): Could not unregister removed application com.test.thalitest
,D/DotMatrix( 1588): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1588): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1588): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,W/GeofencerStateMachine( 1435): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1325): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1325): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  902): acquireWL(43f74ab8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1435 10028 null
D/PMS     (  902): releaseWL(43f74ab8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/VoicemailCleanupService( 1292): Cleaning up data for package: com.test.thalitest
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  902):   Scheme: "sms"
,I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  902): Client connection lost with reason: 4
I/WindowState(  902): WIN DEATH: Window{422fc850 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  902):   Scheme: "smsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/Launcher( 1267): Deferring update until onResume
,D/Launcher( 1267): waitUntilResume // bindAppsRemoved
,W/SystemReader( 1252): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/AccTypeManager( 1325): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PackageBroadcastService( 1226): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  902):   Scheme: "mms"
,I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  902):   Scheme: "mmsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/InputMethodManagerService(  902): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/ActivityManager(  902): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4732 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  902):   Scheme: "sms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,E/ExternalAccountType( 1325): Unsupported attribute readOnly
,I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  902):   Scheme: "smsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/ActivityManager(  902): Delaying start of: ServiceRecord{43fb1088 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  902):   Scheme: "mms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  902):   Scheme: "mmsto"
,I/MultiDex( 4732): install
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/ActivityManager(  902): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4747 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/MultiDex( 4732): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/PeopleContactsSync( 1226): CP2 sync disabled
,I/MultiDex( 4732): loading existing secondary dex files
,I/MultiDex( 4732): load found 1 secondary dex files
,I/MultiDex( 4732): install done
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1226, uid=10028, userID:0
,I/Icing   ( 1226): doRemovePackageData com.test.thalitest
,D/PMS     (  902): acquireWL(43ef34a0): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
I/ProviderInstaller( 4732): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/MultiDex( 4747): install
,I/MultiDex( 4747): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
D/PMS     (  902): releaseWL(43ef34a0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/MultiDex( 4747): loading existing secondary dex files
,I/MultiDex( 4747): load found 1 secondary dex files
,I/MultiDex( 4747): install done
I/ActivityManager(  902): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
,I/ProviderInstaller( 4747): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  902): Resuming delayed broadcast
,D/Process (  902): killProcessQuiet, pid=4362
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 4362:com.android.settings:remote/1000 (adj 15): empty #17
,I/[PluginManager]RegisterService( 1398): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 1398): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1267): action: android.intent.action.PACKAGE_REMOVED
,I/IcingCorporaProvider( 2872): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  902): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4769 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/ActivityManager(  902): Recipient 4362
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  902): acquireWL(42fd74b0): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,E/SQLiteLog( 4732): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 4732): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5c9daaf8
,E/DriveAsyncService( 4732): disk I/O error (code 3850)
E/DriveAsyncService( 4732): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4732): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4732): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4732): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4732): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4732): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4732): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4732): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4732): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4732): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4732): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4732): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4732): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4732): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4732): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 2872): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2872): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63a6b1b0
,E/IcingCorporaProvider( 2872): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2872): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2872): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2872): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2872): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2872): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2872): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2872): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2872): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2872): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2872): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2872): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2872): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2872): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2872): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2872): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2872): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2872): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2872): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2872): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2872): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2872): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2872): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2872): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2872): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2872): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2872): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2872): 	... 15 more
W/IcingCorporaProvider( 2872): notifyTableChanged failed.
,W/IcingCorporaProvider( 2872): Table change notification failed for TableStorageSpec[applications]
,I/IcingCorporaProvider( 2872): UpdateCorporaTask done [took 163 ms] updated apps [took 163 ms] 
D/PMS     (  902): releaseWL(42fd74b0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,E/SQLiteLog( 4732): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
,E/SQLiteDBG( 4732): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5c9daaf8
,E/DocListDatabase( 4732): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4732): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4732): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4732): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4732): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4732): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4732): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4732): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4732): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4732): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4732): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4732): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4732): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4732): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4732): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4732): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4732): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4732): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4732): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4732): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4732): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4732): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4732): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4732): threadid=1: thread exiting with uncaught exception (group=0x41664e30)
,E/AndroidRuntime( 4732): FATAL EXCEPTION: main
E/AndroidRuntime( 4732): Process: com.google.android.gms.drive, PID: 4732
E/AndroidRuntime( 4732): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4732): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4732): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4732): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4732): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4732): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4732): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4732): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4732): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4732): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4732): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4732): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4732): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4732): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4732): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4732): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4732): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4732): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4732): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4732): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4732): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4732): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4732): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4732): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4732): 	... 10 more
E/ActivityManager(  902): App crashed! Process: com.google.android.gms.drive
D/Process ( 4732): killProcess, pid=4732
D/Process ( 4732): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/DropBoxManagerService(  902): Can't write: system_app_crash
E/DropBoxManagerService(  902): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  902): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  902): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  902): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  902): 	... 5 more
,W/PackageManager(  902): Unable to load service info ResolveInfo{423d6ea0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  902): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  902): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  902): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  902): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  902): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  902): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  902): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  902): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  902): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  902): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  902): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  902): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteDatabase( 4769): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4769): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4769): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4769): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4769): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4769): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4769): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4769): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4769): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4769): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4769): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4769): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4769): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4769): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4769): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4769): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4769): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4769): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4769): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4769): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4769): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4769): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4769): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4769): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4769): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4769): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4769): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4769): Couldn't open ClientFlag.db for writing (will try read-only):,
E/SQLiteOpenHelper( 4769): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4769): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4769): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4769): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4769): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4769): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4769): 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4769): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4769): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4769): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4769): 	,at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4769): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4769): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4769): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4769): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4769): 	at aJm.a(Scopes.java:65),
E/SQLiteOpenHelper( 4769): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4769): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4769): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4769): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4769): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4769): 	at Tk.a(ScopedInjector.java:216)
,E/SQLiteOpenHelper( 4769): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4769): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4769): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4769): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
,E/SQLiteOpenHelper( 4769): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4769): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4769): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4769): 	at android.app.ActivityThread.main(ActivityThread.java:5633),
E/SQLiteOpenHelper( 4769): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4769): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4769): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
,E/SQLiteOpenHelper( 4769): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4769): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4769): Opened ClientFlag.db in read-only mode
I/ActivityManager(  902): Recipient 4732
I/ActivityManager(  902): Process com.google.android.gms.drive (pid 4732) has died.
W/ActivityManager(  902): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteDatabase( 4769): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4769): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4769): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4769): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4769): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4769): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4769): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4769): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4769): threadid=11: thread exiting with uncaught exception (group=0x41664e30)
,E/ActivityManager(  902): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4769): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4769): Process: com.google.android.apps.docs, PID: 4769
E/AndroidRuntime( 4769): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4769): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4769): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4769): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4769): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4769): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4769): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  902): Can't write: system_app_crash
E/DropBoxManagerService(  902): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  902): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  902): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  902): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  902): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  902): 	... 5 more
,D/Process ( 4769): killProcess, pid=4769
,D/Process ( 4769): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  902): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4792 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/RemoteDisplayProvider(  902): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  902): start
,I/ActivityManager(  902): Recipient 4769
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  902): killProcessQuiet, pid=4004
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  902): Killing 4004:com.google.android.gm/u0a107 (adj 15): empty #17
I/ActivityManager(  902): Process com.google.android.apps.docs (pid 4769) has died.
,W/AtomicFile(  902): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  902): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,W/ContextImpl( 4792): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  902): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4805 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
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
,W/dalvikvm( 4792): threadid=10: thread exiting with uncaught exception (group=0x41664e30)
,E/ActivityManager(  902): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4792): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4792): Process: com.android.keychain, PID: 4792
E/AndroidRuntime( 4792): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4792): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
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
D/ErrorReport(  902): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4792): killProcess, pid=4792
,D/Process ( 4792): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  902): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  902): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452525875177.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  902): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  902): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  902): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  902): 	... 4 more
,I/ActivityManager(  902): Recipient 4792
,I/ActivityManager(  902): Process com.android.keychain (pid 4792) has died.
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ActivityManager(  902): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10758ms
,D/AppTag  ( 4805): getInstance(Context context)
,D/AppTag  ( 4805): getInstance(Context context)
,D/AppTag  ( 4805): onCreate()
I/ActivityManager(  902): Recipient 4004
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  902): acquireWL(42555088): PARTIAL_WAKE_LOCK  AsyncService 0x1 4154 10160 null
,I/dalvikvm-heap( 4154): Grow heap (frag case) to 16.935MB for 1821008-byte allocation
D/PMS     (  902): releaseWL(42555088): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  902): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4824 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 4824): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4824 dbg=false s=true
,I/DeviceManagement( 4824): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4824): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4824): WorkflowService: Starting workflow service
I/DeviceManagement( 4824): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41ac8240] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4824): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4824): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4824): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4824): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  902): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4838 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 4824): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4824): SessionStateController: Checking invariants...
,D/Documents( 4838): Loading roots for com.android.providers.downloads.documents
,D/Documents( 4838): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 4838): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4838): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4838): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4838): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4838): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4838): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4838): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4838): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4838): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4838): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4838): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4838): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4838): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4838): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4838): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4838): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4838): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4838): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4838): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4838): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4838): threadid=1: thread exiting with uncaught exception (group=0x41664e30)
,D/Process (  902): killProcessQuiet, pid=4449,
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,E/ActivityManager(  902): App crashed! Process: com.android.documentsui
,I/ActivityManager(  902): Killing 4449:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
E/AndroidRuntime( 4838): FATAL EXCEPTION: main
E/AndroidRuntime( 4838): Process: com.android.documentsui, PID: 4838
E/AndroidRuntime( 4838): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4838): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4838): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4838): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4838): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4838): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4838): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4838): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4838): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4838): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4838): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4838): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4838): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4838): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4838): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4838): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4838): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4838): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4838): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4838): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4838): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4838): 	... 10 more
D/ErrorReport(  902): HtcErrorReportManager Begin---add error logs to dropbox,
,I/ActivityManager(  902): Recipient 4449
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/ErrorReport(  902): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  902): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452525875490.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  902): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  902): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  902): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  902): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  902): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  902): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  902): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  902): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  902): 	... 4 more
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/Process ( 4838): killProcess, pid=4838
,D/Process ( 4838): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  902): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4853 uid=10023 gids={50023, 1028, 1015, 1023}
,I/ActivityManager(  902): Recipient 4838
,D/Process (  902): killProcessQuiet, pid=3846
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Killing 3846:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/ActivityManager(  902): Process com.android.documentsui (pid 4838) has died.
D/GCM     ( 1362): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1267): loadItems() com.htc.launcher.pageview.WidgetManager@41b27d98 +
I/Prism.WidgetManager( 1267): onLoadItems() +
,D/ExternalStorage( 4853): After updating volumes, found 1 active roots
I/ActivityManager(  902): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4868 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4824): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4824): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4824): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4824): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4824): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4824): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4824): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4824): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4824): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4824): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4824): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4824): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4824): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4824): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4824): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4824): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4824): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4824): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4824): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4824): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4824): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteDatabase( 4824): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4824): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4824): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4824): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4824): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4824): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4824): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4824): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4824): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4824): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4824): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4824): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4824): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 4824): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41ac8240]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4824): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4824): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4824): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4824): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4824): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4824): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4824): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4824): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4824): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4824): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4824): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4824): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4824): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4824): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4824): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4824): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4824): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4824): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4824): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4824): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4824): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4824): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4824): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4824): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4824): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4824): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4824): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4824): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4824): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4824): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4824): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4824): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4824): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 4824): WorkflowService: Stopping workflow service
I/ActivityManager(  902): Recipient 3846
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  902): Client com.google.android.music (pid 3846): Died!
,E/SQLiteDatabase( 4868): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 4868): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4868): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4868): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4868): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4868): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 4868): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 4868): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 4868): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 4868): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4868): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4868): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4868): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 4868): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4868): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4868): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4868): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4868): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4868): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4868): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4868): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4868): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4868): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4868): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 4868): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 4868): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 4868): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 4868): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4868): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4868): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 4868): Opened MyDB.db in read-only mode
,D/Process (  902): killProcessQuiet, pid=4501
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 4501:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 4501
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0

```
