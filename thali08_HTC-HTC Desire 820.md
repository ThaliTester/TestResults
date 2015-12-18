#### Test 539786633aa3ea0_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1123): WifiActivity: 1
,D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/PMS     (  909): acquireWL(437bfff0): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
D/PMS     (  909): releaseWL(437bfff0): PARTIAL_WAKE_LOCK  Icing 0x1 null
--------- beginning of /dev/log/main
E/cutils-trace( 4345): Error opening trace file: No such file or directory (2)
D/PMS     (  909): acquireWL(437b4f38): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
D/PMS     (  909): releaseWL(437b4f38): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  909): acquireWL(437b1470): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
D/PMS     (  909): releaseWL(437b1470): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  909): acquireWL(437ac448): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
D/PMS     (  909): releaseWL(437ac448): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/CustomizationManager( 4345): ====startRecUseTime====
D/htc.customization.log.level( 4345):  is 
W/CustomizationLogLevel( 4345): Level value is invalid, use default level 2
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  909):    returned true
D/CustomizationManager( 4345):  Read ACC file spent 0.066 (s)
D/CIDMapFileReader( 4345): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4345): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4345): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4345): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4345): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4345): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4345): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4345): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4345): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4345): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4345): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4345): Parsing tag category name = system
I/CustomizationCIDLoader( 4345): Parsing tag category name = application
I/CustomizationCIDLoader( 4345): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4345): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4345): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4345): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4345): Parsing tag category name = Settings
D/CustomizationManager( 4345):  Read CID file spent 0.112 (s)
D/CustomizationManager( 4345):  All configurations done spent 0.112 (s)
W/HtcNativeFlag( 4345): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4345): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4345): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4345): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  909): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  909): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4345
D/PMS     (  909): acquireHCC(437a1440): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 909 1000 null
D/PMS     (  909): acquireHCC(43790fb0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 909 1000 null
W/asset   (  909): Copying FileAsset 0x6a2a3fb8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  909): @test_code: getHtcIntentFlag: 0 obj: 1122815688
I/FeedHostManager( 1276): [onPause]
I/FeedProviderManager( 1276): onPause
I/FeedHostManager( 1276): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@4261af28
I/SocialFeedProvider( 1276): +onPause
I/SocialFeedProvider( 1276): -onPause
D/PMS     (  909): acquireWL(431422f0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 909 1000 null
I/ActivityManager(  909): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4360 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
W/asset   ( 4360): Copying FileAsset 0x5c7bc648 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1276): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4360): Binding Chromium to main looper Looper (main, tid 1) {4250cec0}
I/LibraryLoader( 4360): Expected native library version number "",actual native library version number ""
I/chromium( 4360): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4360): Initializing chromium process, renderers=0
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43899d08:true
W/System.err(  909): java.lang.Throwable: stack dump
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4360): 1112682368: getState(). Returning 12
D/PMS     (  909): acquireWL(42de3488): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  909): acquireWL(42dc13d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  909): releaseWL(42de3488): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4360): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4360): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4360): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4360): Local Branch: 
I/Adreno-EGL( 4360): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4360): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4360):                  aa63bbd948f41d15fc72f585e
W/chromium( 4360): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4360): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4360): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4360): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4360): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4360): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4360): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4360): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4360): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4360): CordovaWebView is running on device made by: HTC
,W/AwContents( 4360): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  909): Disable input method client, pid=1276
,W/ResourceType( 4360): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4360): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@42554630, mServedView=org.apache.cordova.engine.SystemWebView{4251a298 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  909): Enable input method client, pid=4360
W/XT9_C   ( 1217): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1217): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1217): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1217): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4360): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  909): Displayed com.test.thalitest/.MainActivity: +276ms
D/PMS     (  909): releaseWL(431422f0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/ActivityManager(  909): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4403 uid=10077 gids={50077}
D/PMS     (  909): acquireWL(42b01730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10077}
,V/AlarmManager(  909): sending alarm PendingIntent{42efbe30: PendingIntentRecord{42f21858 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450445299613, Int=60000
,D/PMS     (  909): releaseWL(42b01730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/JsMessageQueue( 4360): Set native->JS mode to OnlineEventsBridgeMode
,D/SMSBackup( 4403): SMSBackupAgentService started
,D/SMSBackup( 4403): Checking restore status
D/SMSBackup( 4403): Restore complete
,D/SMSBackup( 4403): cancelCheckAlarm
,D/SMSBackup( 4403): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  909): killProcessQuiet, pid=3269
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3269:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3269
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/jxcore_app_log( 4360): JniHelper::setJavaVM(0x420cc010), pthread_self() = 1663671264
,D/JX-Cordova( 4360): jxcore cordova android initializing
,I/dalvikvm-heap( 4360): Grow heap (frag case) to 11.609MB for 146998-byte allocation
,I/dalvikvm-heap( 4360): Grow heap (frag case) to 11.726MB for 220492-byte allocation
,I/dalvikvm-heap( 4360): Grow heap (frag case) to 11.906MB for 330734-byte allocation
,I/dalvikvm-heap( 4360): Grow heap (frag case) to 12.184MB for 496096-byte allocation
,I/dalvikvm-heap( 4360): Grow heap (frag case) to 12.595MB for 744140-byte allocation
,I/dalvikvm-heap( 4360): Grow heap (frag case) to 14.068MB for 1674304-byte allocation
,I/dalvikvm-heap( 4360): Grow heap (frag case) to 15.501MB for 2511452-byte allocation
,I/dalvikvm-heap( 4360): Grow heap (frag case) to 17.559MB for 3767174-byte allocation
,W/jxcore-log( 4360): Initializing JXcore engine
,W/jxcore-log( 4360): JXcore engine is ready
,W/jxcore-log( 4360): Starting JXcore engine
,W/CpuWake (  909): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): <<nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  909): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>release mCpuPerf_Freq wakelock
D/PMS     (  909): releaseHCC(437a1440): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
W/CpuWake (  909): <<release mCpuPerf_Freq wakelock
,D/PMS     (  909): releaseHCC(43790fb0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4360): Platform android
W/jxcore-log( 4360): 
,W/jxcore-log( 4360): Process ARCH arm
W/jxcore-log( 4360): 
,D/WifiDataStallTracker(  909): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  909): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  909): updateDataStallInfo: mDataStallTxRxSum={txSum=43 rxSum=34} preTxRxSum={txSum=42 rxSum=33}
D/WifiDataStallTracker(  909): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  909): onDataStallAlarm: tag=20198 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=20199 delay=15s
D/PMS     (  909): acquireWL(42ef74a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{42fafd48: PendingIntentRecord{42fc9b30 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=106900, Int=0
D/PMS     (  909): releaseWL(42ef74a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4360): JXcore Cordova bridge is ready!
I/jxcore-log( 4360): 
,W/jxcore-log( 4360): JXcore engine is started
,I/chromium( 4360): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 4360): Skipped 131 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4360): Toggling radios to true
I/jxcore-log( 4360): 
,D/BluetoothAdapter( 4360): enable(): BT is already enabled..!
,D/WifiManager( 4360): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  909): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  909): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  909): Settings:Agentvalue: 2
W/Settings:Agent(  909): >> traceCallingStack()
W/Settings:Agent(  909): Process.myPid(): 909
W/Settings:Agent(  909): Process.myTid(): 920
W/Settings:Agent(  909): Process.myUid(): 1000
W/Settings:Agent(  909): 
W/Settings:Agent(  909): 
,W/System.err(  909): java.lang.Throwable: stack dump
D/WifiService(  909): setWifiEnabled: true pid=4360, uid=10348
E/WifiService(  909): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  909): isSprintWifiRestricted(): false
I/WifiService(  909): isMdmWifiRestricted(): false
D/WifiService(  909): New client listening to asynchronous messages
,D/WifiSettingsStore(  909): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  909): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  909): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  909): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  909): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  909): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  909): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  909): 
W/Settings:Agent(  909): << traceCallingStack(): 1(ms)
D/WifiManager( 4360): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiManager( 4360): reconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  909): doBoolean: DISCONNECT
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): TDLS: Tear down peers
I/wpa_supplicant( 1168): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4360): Radios toggled
I/jxcore-log( 4360): 
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1168): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1168): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  909): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromEventString() 3
I/wpa_supplicant( 1168): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  909): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  909): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1168): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1168): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1168): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1168): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1168): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb82d6bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1168):    addr=c0:ff:d4:d3:aa:48
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 1168): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1168): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1168): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1168): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1168): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  909): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1168): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1168): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1168): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1168): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1168): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1168): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1168): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1168): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1168): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1168): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1168): nl80211: Event message available
D/wpa_supplicant( 1168): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
,D/wpa_supplicant( 1168): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  909):    returned true
D/WifiPerfLock(  909): release()
D/WifiStateMachine(  909): PerfLock released for exiting ConnectedState
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): Power_Mode_Type mode = 0
I/wpa_supplicant( 1168): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/ConnectivityService(  909): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  909): acquireWL(42d83608): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 909 1000 null
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  909):    returned true
D/DhcpStateMachine(  909): [RunningState] Stop DHCP
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/WifiNative-wlan0(  909): doBoolean: RECONNECT
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): Fast associate: Old scan results
I/wpa_supplicant( 1168): wpa_supplicant_scan enter
I/wpa_supplicant( 1168): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1168): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1168): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1168): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1168): nl80211: Event message available
D/wpa_supplicant( 1168): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=20199 mDataStallAlarmIntent=PendingIntent{428a8c88: PendingIntentRecord{42fc9b30 android broadcastIntent}}
D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): Enter handleNetworkDisconnect
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): Power_Mode_Type mode = 0
I/wpa_supplicant( 1168): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  909):    returned true
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1885/10178)
D/ConnectivityService(  909): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/WISPrService( 4140): >>>>>WISPrService start isConnected = false<<<<<
,D/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  909):    returned true
D/UsbnetStateTracker(  909): isAvailable+-
D/UsbnetStateTracker(  909): reconnect
,D/UsbnetStateTracker(  909): isAvailable+-
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  909): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  909): default: reconnect()
D/MDST    (  909): default: setTeardownRequested(false)
D/MDST    (  909): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/WifiService(  909): New client listening to asynchronous messages
D/ConnectivityService(  909): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  909): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/WifiStateMachine(  909): Exit handleNetworkDisconnect
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WISPrService( 4140): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  909): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/ConnectivityService(  909): resetConnections(wlan0, 3)
D/libc    (  363): [NET] entry_id:5   entry:0xb7421818  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb74212d8  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb7421108  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb7421760  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb74211d0  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb7421410  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/PMS     (  909): acquireWL(42f2d548): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  909): acquireWL(42f467c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/ConnectivityService(  909): flush DNS cache for net 1(wlan0)
,D/WISPrService( 4140): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4140): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  909): releaseWL(42f467c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1885/10178)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  909): acquireWL(42f42038): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/ConnectivityService(  909): reportInetCondition for net -1, percentage: 0 by  (1372/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  909): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,I/QuickSettingWifi( 1123): receive.wifiConnect:false wifiAPname:null elapse:1
I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/WifiStateMachine(  909): startScan Pid: 909 Uid 1000
,D/WifiNative-wlan0(  909): doBoolean: SCAN
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  909):    returned false
D/PMS     (  909): releaseWL(42f2d548): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  909): releaseWL(42f42038): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/BatSI   (  909): WIFI scan started for: 650a0300 uid:1000
,D/ConnectivityService(  909): mActiveDefaultNetwork: -1
,I/QuickSettingWifi( 1123): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  909): handleInetConditionChange: no active default network - ignore
,D/PMS     (  909): releaseWL(42dc13d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
,I/NetworkMonitor( 3858): type=WIFI subType= reason=null isConnected=false
D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  909): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  909): NoActiveNetworkState
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (3858/10154)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4245/10100)
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1885/10178)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1925/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1444/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4245/10100)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1276/10075)
D/Tethering(  909): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  909): bSetPropertyMultiRAB:false
I/ConnectivityHelper( 1276): [onReceive] WIFI(1): DISCONNECTED
D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  909): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  909): ipv4Default null
I/Tethering(  909): No IPv4 upstream interface, giving up.
,D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  909): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/PMS     (  909): acquireWL(43a92f80): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/PMS     (  909): releaseWL(43a92f80): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (2427/10021)
,I/ActivityManager(  909): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4426 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4426): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4426): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4426): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4426): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4426): Preparing secondary program dexes.
V/DexLibLoader( 4426): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4426): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4426): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4426): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4426): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4426): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4426): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4426): Dex already copied
D/OdexVerifier( 4426): Odex verification is skipped.
,V/DexLibLoader( 4426): Creating class loader
,V/DexLibLoader( 4426): Finished creating class loader
V/DexLibLoader( 4426): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4426): Dex already copied
D/OdexVerifier( 4426): Odex verification is skipped.
,V/DexLibLoader( 4426): Creating class loader
,V/DexLibLoader( 4426): Finished creating class loader
V/DexLibLoader( 4426): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4426): Dex already copied
D/OdexVerifier( 4426): Odex verification is skipped.
,V/DexLibLoader( 4426): Creating class loader
,V/DexLibLoader( 4426): Finished creating class loader,
V/DexLibLoader( 4426): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4426): Dex already copied
D/OdexVerifier( 4426): Odex verification is skipped.
,V/DexLibLoader( 4426): Creating class loader
,V/DexLibLoader( 4426): Finished creating class loader
,V/DexLibLoader( 4426): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4426): DexLibLoader.ensureDexLoaded took 17 ms
,W/dalvikvm( 4426): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4426): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4426): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4426): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4426): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4426): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4426): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,W/dalvikvm( 4426): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4426): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1168): nl80211: Event message available
D/wpa_supplicant( 1168): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1168): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1168): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1168): nl80211: Survey data missing
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1168): Sorted scan results
I/wpa_supplicant( 1168): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1168): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1168): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1168): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1168): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-78
I/wpa_supplicant( 1168): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-87
I/wpa_supplicant( 1168): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
D/wpa_supplicant( 1168): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1168): Add randomness: count=9 entropy=0
D/wpa_supplicant( 1168): Add randomness: count=10 entropy=1
D/wpa_supplicant( 1168): Add randomness: count=11 entropy=2
D/wpa_supplicant( 1168): Add randomness: count=12 entropy=3
D/wpa_supplicant( 1168): Add randomness: count=13 entropy=4
D/wpa_supplicant( 1168): Add randomness: count=14 entropy=5
D/wpa_supplicant( 1168): Add randomness: count=15 entropy=6
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1168): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1168): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1168): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1168): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1168): wpa_supplicant_pick_network+
I/wpa_supplicant( 1168): Selecting BSS from priority group 1
I/wpa_supplicant( 1168): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1168): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1168): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1168): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1168): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1168):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1168):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-51
I/wpa_supplicant( 1168): Start print parameters
I/wpa_supplicant( 1168): wpa_s->wpa_state is 3
I/wpa_supplic,ant( 1168): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1168): isConcurrentMode() is 0
I/wpa_supplicant( 1168): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1168): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1168): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1168): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1168): wpa_s->reassociate is 1
I/wpa_supplicant( 1168): wpa_s->is_screen_on 1
I/wpa_supplicant( 1168): wpa_s->ifname wlan0
I/wpa_supplicant( 1168): End print parameters
I/wpa_supplicant( 1168): selected network = 1
D/wpa_supplicant( 1168): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb82d84e8  current_ssid=0x0
D/wpa_supplicant( 1168): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1168): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1168): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1168): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1168): check if in concurrent case
I/wpa_supplicant( 1168): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1168): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1168): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1168): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1168): RSN: PMKSA cache search - network_ctx=0xb82d84e8 try_opportunistic=0
D/wpa_supplicant( 1168): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1168): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1168): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1168): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1168): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1168): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1168): nl80211: Unsubscribe mgmt frames handle 0xb82d7718 (mode change)
D/wpa_supplicant( 1168): nl80211: Subscribe to mgmt frames with non-AP handle 0xb82d7718
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1168):   * bssid=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 1168):   * freq=2412
D/wpa_supplicant( 1168):   * Auth Type 0
D/wpa_supplicant( 1168):   * WPA Versions 0x2
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1168): nl80211: Connect request send successfully
D/wpa_supplicant( 1168): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1168): reply (921) for get BSS: id=0
I/wpa_supplicant( 1168): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1168): freq=5220
I/wpa_supplicant( 1168): level=-50
I/wpa_supplicant( 1168): tsf=0000000109741890
I/wpa_supplicant( 1168): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1168): ssid=NG7005g
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=1
I/wpa_supplicant( 1168): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1168): freq=2412
I/wpa_supplicant( 1168): level=-51
I/wpa_supplicant( 1168): tsf=0000000109741909
I/wpa_supplicant( 1168): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1168): ssid=NG700
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=2
I/wpa_supplicant( 1168): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1168): freq=2427
I/wpa_supplicant( 1168): level=-73
I/wpa_supplicant( 1168): tsf=0000000109741913
I/wpa_supplicant( 1168): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1168): ssid=Gonzos
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=3
I/wpa_supplicant( 1168): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1168): freq=2437
I/wpa_supplicant( 1168): level=-78
I/wpa_supplicant( 1168): tsf=0000000109741917
I/wpa_supplicant( 1168): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1168): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=4
I/wpa_supplicant( 1168): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1168): freq=2437
I/wpa_supplicant( 1168): level=-88
I/wpa_supplicant( 1168): tsf=0000000109741925
I/wpa_supplicant( 1168): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1168): ssid=UPC4688432
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=5
I/wpa_supplicant( 1168): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1168): freq=2462
I/wpa_supplicant( 1168): level=-87
I/wpa_supplicant( 1168): tsf=0000000109741921
I/wpa_supplicant( 1168): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1168): ssid=UPC Wi-Free
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=6
I/wpa_supplicant( 1168): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1168): freq=2412
I/wpa_supplicant( 1168): level=-51
I/wpa_supplicant( 1168): tsf=0000000109741905
I/wpa_supplicant( 1168): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1168): ssid=01ABC
I/wpa_supplicant( 1168): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 109741890, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 2412, timestamp: 109741909, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 109741913, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -78, frequency: 2437, timestamp: 109741917, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (7) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 109741925, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2462, timestamp: 109741921, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -51, frequency: 2412, timestamp: 109741905, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 7 to mScanResults
D/BatSI   (  909): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,E/FbInjectorInitializer( 4426): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1168): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1168): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1168): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1168): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1168): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1168): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1168): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1168): nl80211: Event message available
D/wpa_supplicant( 1168): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1168): nl80211: Connect event
D/wpa_supplicant( 1168): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1168): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1168): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1168): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1168): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1168): Add randomness: count=16 entropy=7
I/wpa_supplicant( 1168): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1168): TDLS: Remove peers on association
D/wpa_supplicant( 1168): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1168): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1168): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1168): EAPOL: enable timer tick
D/wpa_supplicant( 1168): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1168): htc_wext_set_keepalive +
I/wpa_supplicant( 1168): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1168): getPrivFuncNum +	
I/wpa_supplicant( 1168): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1168): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1168): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1168): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1168): Get randomness: len=32 entropy=8
D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
D/Tethering(  909): interfaceStatusChanged wlan0, true
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  909): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  909): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  909): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
,D/WifiMonitor(  909): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  909): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  909): Enter handleAssociatedWithEvent
D/WifiStateMachine(  909): Associated
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  909): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  909): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  909): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 1168): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb82d79f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1168):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1168): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1168): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f68b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1168):    broadcast key
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1168): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP],
E/wpa_supplicant( 1168): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1168): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1168): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1168): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
E/wpa_supplicant( 1168): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP),
D/wpa_supplicant( 1168): netlink: Operstate: linkmode=-1, operstate=6
D/WifiStateMachine(  909): This record is existed, only update it...
I/wpa_supplicant( 1168): set send_ind_to_ndc = 0
,I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING (1)+
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1168): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1168): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1168): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1168): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1168): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1168): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1168): EAPOL authentication completed successfully
I/wpa_supplicant( 1168): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1168): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1168): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1168): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
D/Tethering(  909): interfaceStatusChanged wlan0, true
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/WifiStateMachine(  909): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  909): This record is existed, only update it...
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/BluetoothManagerService(  909): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
I/jxcore-log( 4360): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4360): 
I/jxcore-log( 4360): my name is : HTC-HTC Desire 820_PT2576
I/jxcore-log( 4360): 
D/WISPrService( 4140): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WISPrService( 4140): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/DhcpStateMachine(  909): [StoppedState] Start DHCP
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=100 [2][2][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): Power_Mode_Type mode = 1
I/wpa_supplicant( 1168): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  909):    returned null
E/WifiStateMachine(  909): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  909):    returned null
D/WifiStateMachine(  909): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  909): acquireWL(44abe398): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 909 1000 null
D/WifiStateMachine(  909): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4295a1b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4295a1b0 target=com.android.internal.util.StateMachine$SmHandler }
,W/fb4a(:<default>):StaticBindingVerifier( 4426): Verify
,I/QuickSettingWifi( 1123): receive.wifiConnect:false wifiAPname:null elapse:1
,I/jxcore-log( 4360): attempting to connect to test coordinator
I/jxcore-log( 4360): 
,I/jxcore-log( 4360): check test folder
I/jxcore-log( 4360): 
,I/jxcore-log( 4360): found test : ./testFindPeers.js
I/jxcore-log( 4360): 
,I/jxcore-log( 4360): found test : ./testReConnect.js
I/jxcore-log( 4360): 
,I/jxcore-log( 4360): found test : ./testSendData.js
I/jxcore-log( 4360): 
,I/jxcore-log( 4360): Test app app.js loaded
I/jxcore-log( 4360): 
,I/Choreographer( 4360): Skipped 159 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4360): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4360): 
,I/chromium( 4360): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiService(  909): New client listening to asynchronous messages
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4426): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4426): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4426): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  909): killProcessQuiet, pid=3840
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 3840:com.htc.mediamanager/u0a32 (adj 15): empty #17
,D/PMS     (  909): acquireWL(43aa15d0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1230 10028 null
I/ActivityManager(  909): Recipient 3840
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(441aedc0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1230 10028 null
,D/PMS     (  909): releaseWL(43aa15d0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,D/GCM     ( 1372): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  909): releaseWL(441aedc0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,D/AutoSetting( 1405): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  909): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4455 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1405/10053)
,D/AutoSetting( 1405): Util - no network available!
,D/AutoSetting( 1405): service - onCreate()
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1405/10053)
D/AutoSetting( 1405): service - AddressCache: using context: com.htc.Weather
D/LocationManagerService(  909): request 42f720c8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  909): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1405): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1405): service - mHandler: cancel location update
D/AutoSetting( 1405): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4426): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4426): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4426): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4455): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4455): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4455): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4455): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  909): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4471 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4455/10078)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4455/10078)
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4455/10078)
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4426): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,I/ActivityManager(  909): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4497 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  909): killProcessQuiet, pid=4188
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 4188:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/dalvikvm-heap( 4426): Grow heap (frag case) to 9.963MB for 84664-byte allocation
,E/dalvikvm( 4426): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4426): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4497): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4497): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4497): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4497): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4497): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4426): Grow heap (frag case) to 9.974MB for 28144-byte allocation
,E/dalvikvm( 4426): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4426): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4426): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4426): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4426): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4426): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4426): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4426): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4426): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4426): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4426): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4426): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4426): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4426): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4426): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4426): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1168): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,I/dalvikvm-heap( 4426): Grow heap (frag case) to 10.017MB for 39954-byte allocation
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 4188
D/WifiService(  909): Client connection lost with reason: 4
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  909): releaseWL(44abe398): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): gateway: /192.168.1.1
,D/WifiNative-wlan0(  909): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  909): VerifyingLinkState enter
D/WifiStateMachine(  909): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  909): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  909): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WIFI_ICON( 1123): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=20201 delay=15s
I/dalvikvm-heap( 4426): Grow heap (frag case) to 10.092MB for 79892-byte allocation
,I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  909): WAN detection
V/NetworkPolicy(  909): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  909): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  909): default: teardown()
D/MDST    (  909): default: setTeardownRequested(true)
D/MDST    (  909): default: setEnableApn apnType =default , enable=false
,D/WISPrService( 4140): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  909): default: setTeardownRequested(true)
D/ConnectivityService(  909): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  909): Unexpected mtu value: android.net.wifi.WifiStateTracker@42e407d0
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  909): syncGetConfiguredNetworks
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/ConnectivityService(  909): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  909): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  909): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  909): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  909): acquireWL(430f62c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4455/10078)
,D/WirelessDisplayService(  909): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WirelessDisplayService(  909):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
,I/QuickSettingWifi( 1123): receive.wifiConnect:true wifiAPname:NG700 elapse:2
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/PMS     (  909): acquireWL(43d9fc60): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1230 10028 null
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
D/PMS     (  909): acquireWL(43ff42a0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1230 10028 null
D/PMS     (  909): releaseWL(43d9fc60): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
I/CheckinService( 1230): Preparing to send checkin request
,I/EventLogService( 1230): Accumulating logs since 1450445251552
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4497/10151)
,V/WebViewChromiumFactoryProvider( 4497): Binding Chromium to main looper Looper (main, tid 1) {42512160}
,I/LibraryLoader( 4497): Expected native library version number "",actual native library version number ""
,I/chromium( 4497): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4497): Initializing chromium process, renderers=0
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 1230): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1230): Using GMS GoogleHttpClient
,D/ConnectivityService(  909): mActiveDefaultNetwork: WIFI
,D/PMS     (  909): acquireWL(43bd0f80): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  909): acquireWL(43e700e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,I/jxcore-log( 4360): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4360): 
D/PMS     (  909): releaseWL(43bd0f80): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,E/AudioManagerAndroid( 4497): BLUETOOTH permission is missing!
,D/PMS     (  909): releaseWL(430f62c8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [2][0][0]
,I/dalvikvm-heap( 4426): Grow heap (frag case) to 10.280MB for 75760-byte allocation
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (1230/10028)
,D/ConnectivityService(  909): getNetworkInfo networkType=0 called by com.google.android.gms (1230/10028)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,I/Adreno-EGL( 4497): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4497): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4497): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4497): Local Branch: 
I/Adreno-EGL( 4497): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4497): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4497):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4403d810 u0 ReceiverList{4400dc90 4426 com.facebook.katana/10026/u0 remote:43feb320}}
W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4403d810 u0 ReceiverList{4400dc90 4426 com.facebook.katana/10026/u0 remote:43feb320}}
W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4454f5f8 u0 ReceiverList{4454f598 4426 com.facebook.katana/10026/u0 remote:44543df0}},
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,I/NSApplication( 4497): Starting up...
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4497/10151)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4497/10151)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,D/Process (  909): killProcessQuiet, pid=3971
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4117/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4117/10160)
D/PMS     (  909): acquireWL(43a50d90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1444 10028 null
,I/ActivityManager(  909): Killing 3971:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1123): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1230): awaiting user notification for token
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{42631e20 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1885/10178)
D/PMS     (  909): releaseWL(43a50d90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/RemoteViews.Performance( 1123): com.google.android.gms 2 8 2 12
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1885/10178)
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1885/10178)
,D/wpa_supplicant( 1168): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1168): EAPOL: disable timer tick
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3971
,D/GCoreFlp( 1444): Unknown pending intent to remove.
D/PMS     (  909): acquireWL(44d3c3d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1444 10028 null
D/PMS     (  909): releaseWL(44d3c3d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  909): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4565 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4565): install
,I/MultiDex( 4565): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4565): loading existing secondary dex files
,I/MultiDex( 4565): load found 1 secondary dex files
,I/MultiDex( 4565): install done
,I/ProviderInstaller( 4565): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4426): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4426): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/Adreno-EGL( 4565): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4565): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4565): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4565): Local Branch: 
I/Adreno-EGL( 4565): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4565): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4565):                  aa63bbd948f41d15fc72f585e
,I/PMS     (  909): Going to sleep due to screen timeout...
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42b88ae8
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Light sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42b88ae8, eanble = 0, strlen(mName) = 59
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  909): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42ba9400
W/SensorService(  909): Listener[1] = com.htc.smartdim.sensor_eye@42fd6db0
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  909): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  909): Couldn't get kernel wake lock stats
V/LightsService(  909): setLight #2: color=#0
D/qdlights(  909): set_light_buttons_func: on=0 brightness=0
V/LightsService(  909): setLight #0: color=#0
,D/WirelessDisplayService(  909): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  909): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  909): mWirelessDisplayManager is null
,D/WIFI_ICON( 1123): WifiActivity: 3
,D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  909): releaseWL(42d83608): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  909): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
,D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  909): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,V/Tethering(  909): bSetPropertyMultiRAB:false
D/PMS     (  909): acquireWL(42ceb1e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/PMS     (  909): releaseWL(42ceb1e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.musicenhancer (3879/10051)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1925/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4245/10100)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4455/10078)
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1885/10178)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1444/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1276/10075)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/acms    ( 1925): Checking Certificates
I/acms    ( 1925): Checking Developer Certificates
I/acms    ( 1925): Checking Application Certificates
I/acms    ( 1925): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1925): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1925): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1925): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1925): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1925): Updating next query delay: 75600000
I/mlserverapp( 1925): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1925): cancelACMSProgrammedChecks
,I/Tethering(  909): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
D/CaptivePortalTracker(  909): NoActiveNetworkState
I/Tethering(  909): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/NetworkMonitor( 3858): type=WIFI subType= reason=null isConnected=true
,I/Tethering(  909): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
I/Tethering(  909): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  909): Found interface wlan0
,D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/ConnectivityHelper( 1276): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (3858/10154)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(425961d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4245/10100)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
D/PMS     (  909): releaseWL(425961d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (2427/10021)
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): acquireWL(43ca9338): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1230 10028 null
,D/PMS     (  909): releaseWL(43ca9338): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1372): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,D/PMS     (  909): acquireWL(44a9d7b8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1372 10028 null
D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1372): [NET] getaddrinfo-,err=8
D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1372): [NET] getaddrinfo-, 1
D/libc    ( 1372): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =166c +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
D/AutoSetting( 1405): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4455): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4455): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1405): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1405): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1405): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1405): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1405/10053)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1405/10053)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4497/10151)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4117/10160)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4117/10160)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1885/10178)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 277
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1372): [NET] getaddrinfo_proxy-, success
,I/dalvikvm-heap( 4117): Grow heap (frag case) to 13.500MB for 1821008-byte allocation
,D/SurfaceControl(  909): Excessive delay in blankDisplay() while turning screen off: 374ms
D/PMS     (  909): nativeSetInteractive:false
D/PMS     (  909): nativeSetInteractive:false done
D/PMS     (  909): nativeSetAutoSuspend:true
D/PMS     (  909): nativeSetAutoSuspend:true done
D/HABCtrl (  909): TPE algorithm. remove timeout.
I/InputManager(  909): Cancel all due to getting PMS screen off broadcast
D/PMS     (  909): OOBE c monitor 11
I/InputMethodManagerService(  909): screenObserver, isScreenOn=false
D/NfcService( 1262): ScreenObserver: OFF
D/NfcService( 1262): applyRouting - 0
,I/IntentController( 1123): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1262): applyRouting -2
V/KeyguardServiceDelegate(  909): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42fec580)
W/ResourceType( 4360): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4360): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{4251a298 VFEDH.C. .F...... 0,0-720,1134 #64}
,V/KeyguardServiceDelegate(  909): **** SHOWN CALLED ****
I/InputMethodManagerService(  909): Disable input method client, pid=4360
D/PMS     (  909): acquireWL(44a5dc58): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1262 1027 null
D/PMS     (  909): releaseWL(44a5dc58): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  909): wakingUp
I/WindowManager(  909): No lock screen! windowToken=null
D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1372): [NET] getaddrinfo-,err=8
D/PMN     (  909): onScreenOn
D/PMS     (  909): acquireWL(43d65d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(43d65d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1123): closing low battery warning: level=100
,D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/MtpService( 2427): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1262): applyRouting - 0
D/MtpService( 2427): [MTP][onReceive]-
,D/NfcService( 1262): applyRouting -2
,D/AutoSetting( 1405): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  909): acquireWL(44a7a2e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1262 1027 null
D/PMS     (  909): releaseWL(44a7a2e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  909): acquireWL(4403e778): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/WirelessDisplayService(  909): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/AlarmManager(  909): ACTION_SCREEN_ON
I/AlarmManager(  909): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done recovering
I/AlarmManager(  909): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(4403e778): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
I/ClockThread( 1123): stop update clock
,D/AutoSetting( 1405): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=20202 delay=15s
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4565/10028)
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 1
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): SET_SCREEN_ON:On
I/wpa_supplicant( 1168): htc_wext_set_keepalive +
I/wpa_supplicant( 1168): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1168): getPrivFuncNum +	
I/wpa_supplicant( 1168): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1168): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1168): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING - ret = 0
D/TetherSettings( 4140): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4140): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4140): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4140): Cust_ConnectToPC   : spcsc>false
D/        ( 4140): Cust_ConnectToPC   : IPT>true
D/        ( 4140): Cust_ConnectToPC   : Singel_USB>false
D/WifiNative-wlan0(  909):    returned true
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [5][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  909): BroadcastRSSIForIMS, newrssi =-52 , oldRssi= -200
W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  371): ParamSet string: screen_state=on
W/Settings( 4140): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  909):    returned true
E/SmartNS_Utility( 4140): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4140): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4140): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4140): onReceive:android.intent.action.USER_PRESENT
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
D/WIFI_ICON( 1123): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/ContextImpl( 4140): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,I/SmartNS_PSService( 4140): onReceive:android.intent.action.USER_PRESENT
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
W/Settings( 4140): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4140):  defaultType:0
W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
D/NetworkPolicy(  909): updateScreenOn: false
,I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4607 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/jxcore-log( 4360): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4360): 
,D/GCM     ( 1372): Connected
D/PMS     (  909): acquireWL(445f55c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
,W/Settings( 4565): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
,D/PMS     (  909): acquireWL(44060568): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1444 10028 null
,I/Adreno-EGL( 4565): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4565): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4565): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4565): Local Branch: 
I/Adreno-EGL( 4565): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4565): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4565):                  aa63bbd948f41d15fc72f585e
D/PMS     (  909): releaseWL(44a9d7b8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1854): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1854): onScreenOn: 1450445306694
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1854): onScreenOn: 1450445306694
D/PMS     (  909): releaseWL(44060568): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42ba9400
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42ba9400, eanble = 0, strlen(mName) = 91
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  909): Listener[0] = com.htc.smartdim.sensor_eye@42fd6db0
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/ContextImpl( 4607): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
D/PMN     (  909): goingToSleep
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  909): acquireWL(43a7fa30): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 909 1000 null
,D/PMS     (  909): releaseWL(445f55c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/SmartSyncUtils( 4607): isEpsOn(), nState = 0
,I/Adreno-EGL( 4565): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4565): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4565): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4565): Local Branch: 
I/Adreno-EGL( 4565): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4565): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4565):                  aa63bbd948f41d15fc72f585e
D/PMS     (  909): acquireWL(4403f470): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4607 1000 null
D/PMS     (  909): acquireWL(445cd2a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
D/AlarmManager(  909): ACTION_SCREEN_OFF
I/AlarmManager(  909): [AlarmQueuing] screen off now: 
I/AlarmManager(  909): [AlarmQueuing] data connection: true
I/AlarmManager(  909): [AlarmQueuing] wifi connection: true
,D/PMS     (  909): releaseWL(43a7fa30): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=20202 mDataStallAlarmIntent=PendingIntent{43dd0e20: PendingIntentRecord{42fc9b30 android broadcastIntent}}
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): SET_SCREEN_ON:Off
I/wpa_supplicant( 1168): htc_wext_set_keepalive +
I/wpa_supplicant( 1168): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1168): getPrivFuncNum +	
I/wpa_supplicant( 1168): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1168): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1168): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1168): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1168): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  909):    returned true
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): acquireWL(42de03f8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 909 1000 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  909): releaseWL(4403f470): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
,D/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  909):    returned true
,D/GCM     ( 1372): Message class mpf
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  909): updateScreenOn: false
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
D/PMS     (  909): releaseWL(42de03f8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
,D/SmartSyncUtils( 4607): getMobilePolicyEnabled, result = true
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  909): releaseWL(445cd2a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  909): acquireWL(43fa81e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/Process (  909): killProcessQuiet, pid=4215
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [4][0][0]
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  909): Killing 4215:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/PMS     (  909): releaseWL(43fa81e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/ActivityManager(  909): Recipient 4215
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4607): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4607): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4607): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4607): isEpsOn(), nState = 0
,D/ContactMessageStore( 1249): start background delete task...
I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42fd6db0
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 1
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42fd6db0, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Proximity sensor
D/ContactMessageStore( 1249): size: 0 , 0
D/ContactMessageStore( 1249): Background delete complete
D/WifiService(  909): New client listening to asynchronous messages
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 0
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42fd6db0, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42fd6db0
E/ActivityThread(  909): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4303dc80 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4303dc80 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  909): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  909): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  909): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  909): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  909): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  909): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  909): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  909): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] getTotalRam: 1873 Mb
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1854): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1854): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1854): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1854): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1854): onScreenOff
D/PMS     (  909): acquireWL(43fead30): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1444 10028 null
,D/PMS     (  909): releaseWL(43fead30): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/AutoSetting( 1405): service - mHandler: cancel location update
D/AutoSetting( 1405): service -           changes count: 0
,I/CheckinTask( 1230): Sending checkin request (9009 bytes)
D/libc    ( 1230): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1230): [NET] getaddrinfo-,err=8
D/libc    ( 1230): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1230): [NET] getaddrinfo-, 1
,D/libc    ( 1230): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6602 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 233
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1230): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1230): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1230): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=11 [9][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,W/fb4a(:<default>):UserScope( 4426): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4426): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=20 [5][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/PMS     (  909): acquireWL(44ab1fe0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/PMS     (  909): releaseWL(44ab1fe0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (1230/10028)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  909): getNetworkInfo networkType=0 called by com.google.android.gms (1230/10028)
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/fb4a(:<default>):LocalFbBroadcastManager( 4426): Called registerBroadcastReceiver twice.
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1230): awaiting user notification for token
,I/RemoteViews( 1123): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{428f1d48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.google.android.gms 2 8 2 12
,I/CheckinTask( 1230): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1230): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,D/PMS     (  909): releaseWL(43ff42a0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread( 1230): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@425d54f8 that was originally bound here
E/ActivityThread( 1230): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@425d54f8 that was originally bound here
E/ActivityThread( 1230): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1230): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1230): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1230): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1230): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1230): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1230): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1230): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1230): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1230): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1230): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1230): 	at bks.a(SourceFile:298)
E/ActivityThread( 1230): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1230): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1230): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1372): GCM config loaded
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
D/libc    (  909): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/libc    (  363): [NET] +++++ res_nsend xid =f285 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  909): Find DNS Address www.htc.com/23.59.123.86
,D/PMS     (  909): releaseWL(43e700e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiStateMachine(  909): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,I/jxcore-log( 4360): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4360): 
,W/dalvikvm( 4360): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4360): threadid=1: thread exiting with uncaught exception (group=0x420dde30)
,E/ActivityManager(  909): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4360): FATAL EXCEPTION: main
E/AndroidRuntime( 4360): Process: com.test.thalitest, PID: 4360
E/AndroidRuntime( 4360): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4360): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4360): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4360): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4360): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4360): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4360): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4360): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4360): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4360): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4360): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4360): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4360): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4360): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4360): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4360): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4360): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4360): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4360): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  909):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  909): killProcessQuiet, pid=4245
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,I/ActivityManager(  909): Killing 4245:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process ( 4360): killProcess, pid=4360
D/Process ( 4360): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  909): Recipient 4245
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/JavaBinder(  909): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  909): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1217): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  909): Got RemoteException sending setActive(false) notification to pid 4360 uid 10348
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 4360
D/WifiService(  909): Client connection lost with reason: 4
,I/ActivityManager(  909): Process com.test.thalitest (pid 4360) has died.
,I/WindowState(  909): WIN DEATH: Window{42d49838 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/GAV2    ( 4497): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  909): acquireWL(43a46f30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1444 10028 null
,D/PMS     (  909): acquireWL(446609c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1444 10028 null
,D/PMS     (  909): releaseWL(43a46f30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  909): releaseWL(446609c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/AutoSetting( 1531): service - handleMessage() stop self
,D/AutoSetting( 1531): service - onDestroy() END
,D/AutoSetting( 1531): service - handleMessage() quit looper
,D/Process (  909): killProcessQuiet, pid=4268
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4268:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4268
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  909): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{44629ec8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService},
,D/PMS     (  909): acquireWL(42f81db8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(42f81db8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1405): service - mHandler: update timezone
,D/AutoSetting( 1531): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1531): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1531): service - onCreate()
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1531): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1531): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1593): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1531): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1531): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1531): service - mHandler: update timezone
,D/AutoSetting( 1531): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1531): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1531): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1531): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/PhoneStatusBar( 1123): removeNotification.gc:64
,I/RemoteViews( 1123): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{42660230 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.htc.htclocationservice 2 6 2 11
,D/GpsLocationProvider(  909): ALARM_XTRA_TIMEOUT
,D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  909): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  909): acquireWL(42f27920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{42d440a8: PendingIntentRecord{42e59a50 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141789, Int=0
D/PMS     (  909): acquireWL(43e6fdc8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
V/AlarmManager(  909): sending alarm PendingIntent{439001e8: PendingIntentRecord{42f17b50 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142278, Int=0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
V/AlarmManager(  909): sending alarm PendingIntent{440bf2e0: PendingIntentRecord{42d83b70 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450445324602, Int=1800000
,D/PMS     (  909): acquireWL(441b0208): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/PMS     (  909): releaseWL(441b0208): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =1912 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  909): acquireWL(44069098): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1230 10028 null
,D/PMS     (  909): releaseWL(42f27920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  909): acquireWL(43092560): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1230 10028 null
,D/PMS     (  909): releaseWL(44069098): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 1230): Aggregate from 1450445305207 (log), 1450443524545 (data)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 45
D/libc    (  363): [NET]res_nsend:resplen=238
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
I/global  (  909): call createSocket() return a new socket.
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
D/AutoSetting( 1405): service - handleMessage() stop self
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/AutoSetting( 1405): service - onDestroy() END
,D/AutoSetting( 1405): service - handleMessage() quit looper
,D/PMS     (  909): releaseWL(43092560): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/GpsLocationProvider(  909): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  909): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  909): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  909):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  909): acquireWL(43ff56e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=145428, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43ff56e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): releaseWL(43e6fdc8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  909): killProcessQuiet, pid=3879
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3879:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3879
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{44017a98 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1531): service - handleMessage() stop self
,D/AutoSetting( 1531): service - onDestroy() END
,D/AutoSetting( 1531): service - handleMessage() quit looper
,D/Process (  909): killProcessQuiet, pid=4286
,I/ActivityManager(  909): Killing 4286:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  909): Recipient 4286
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(449c4080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  909): releaseWL(449c4080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1249): switchBindHtcMsgCursor: null
,D/PMS     (  909): acquireWL(43fa9f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): releaseWL(43fa9f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1123): closing low battery warning: level=100
,D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(43861700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=205428, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43861700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4385ad00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10026}
,V/AlarmManager(  909): sending alarm PendingIntent{42f10198: PendingIntentRecord{435b26a0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=230733, Int=0
,I/ActivityManager(  909): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4653 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  909): sending alarm PendingIntent{42ed0008: PendingIntentRecord{42ee8788 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450445415380, Int=10800000
,D/PMS     (  909): releaseWL(4385ad00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.aurora (4653/10047)
,D/Process (  909): killProcessQuiet, pid=4232
,I/ActivityManager(  909): Killing 4232:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  909): Recipient 4232
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,D/PMS     (  909): acquireWL(42ffab68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10026}
,V/AlarmManager(  909): sending alarm PendingIntent{42fd04b0: PendingIntentRecord{434170c8 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=231829, Int=120000
,V/AlarmManager(  909): sending alarm PendingIntent{436d6600: PendingIntentRecord{435b26a0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=232160, Int=0
,D/PMS     (  909): acquireWL(42feeb30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42feeb30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): releaseWL(42ffab68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(42fc8770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42fc8770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,D/PowerUI ( 1123): closing low battery warning: level=100
I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(42ec4520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=265429, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42ec4520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(42ebdc28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(42ebdc28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(4301aee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4301aee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1123): closing low battery warning: level=100
,D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43606478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=325428, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43606478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  909): acquireWL(42eefe90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(42eefe90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(42ad3f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10028}
,V/AlarmManager(  909): sending alarm PendingIntent{43429be0: PendingIntentRecord{44349f98 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1450445554776, Int=0
,D/PMS     (  909): releaseWL(42ad3f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,W/Uploader( 1230): No account for auth token provided
,D/libc    ( 1230): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1230): [NET] getaddrinfo-,err=8
D/libc    ( 1230): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1230): [NET] getaddrinfo-, 1
,D/libc    ( 1230): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =ed2 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE,
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 69
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1230): [NET] getaddrinfo_proxy-, success
,I/global  ( 1230): call createSocket() return a new socket.
D/libc    ( 1230): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 1230): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1230): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1230): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1372): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1372): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1372): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1372): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1372): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1123): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{4256cc08 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4079): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4079): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4079): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4079): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4079): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4079): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4079): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4079): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1123): com.google.android.gms 1 9 4 12
,D/libc    ( 4079): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4079): [NET] getaddrinfo-,err=8
D/libc    ( 4079): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4079): [NET] getaddrinfo-, 1
,D/libc    ( 4079): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6abe +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4079): [NET] getaddrinfo_proxy-, success
I/global  ( 4079): call createSocket() return a new socket.
D/libc    ( 4079): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4079): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4079): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4079): [NET] getaddrinfo-,err=8
,D/PMS     (  909): acquireWL(42a86978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42a86978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1123): closing low battery warning: level=100
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(44a9fa90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=385428, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(44a9fa90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(42fe4d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-,
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(42fe4d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(43019a50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43019a50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(4453b638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=445428, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4453b638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(43ac8138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1123): closing low battery warning: level=100
,D/HtcPowerSaver(  909): updateBatteryInfo
I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): releaseWL(43ac8138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(42fce1a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=505429, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42fce1a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(44365ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10026}
,V/AlarmManager(  909): sending alarm PendingIntent{42feb618: PendingIntentRecord{434170c8 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=532169, Int=300000
,D/PMS     (  909): releaseWL(44365ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(44a97350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(44a97350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=100
,D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4275dc08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=565429, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4275dc08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(44464210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(44464210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(44a3e4a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(44a3e4a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1249): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1249): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1249): sku_id=99
D/ContactMessageStore( 1249): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1249): start background delete task...,
D/ContactMessageStore( 1249): size: 0 , 0
,D/ContactMessageStore( 1249): Background delete complete,
,D/PMS     (  909): acquireWL(44622eb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=625428, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(44622eb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(445f23a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): releaseWL(445f23a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1123): closing low battery warning: level=100
,D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus,
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(44482670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(44482670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/PMS     (  909): acquireWL(43a90278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=685429, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43a90278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(430ebfd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(430ebfd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,D/PowerUI ( 1123): closing low battery warning: level=100
,D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/Process (  909): killProcessQuiet, pid=4303
,I/ActivityManager(  909): Killing 4303:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  909): Recipient 4303
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(4379bc70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/PMS     (  909): releaseWL(4379bc70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43aa3968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=745428, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43aa3968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42ff0dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{427d8800: PendingIntentRecord{42eac710 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=769430, Int=0
,D/PMS     (  909): acquireWL(43b5fed8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 909 1000 null
,D/PMS     (  909): releaseWL(42ff0dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(43101718): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(43b5fed8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  909): releaseWL(43101718): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  909): acquireWL(445f72a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(445f72a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(449c3d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(449c3d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4460e7f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=805429, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4460e7f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(44a76d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(44a76d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(437bb0f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(437bb0f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42d6fb28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=865429, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42d6fb28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1168): nl80211: Event message available
D/wpa_supplicant( 1168): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1168): nl80211: Disconnect event
I/wpa_supplicant( 1168): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1168): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  909): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  909): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  909): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  909): Enter handleNetworkDisconnect
I/wpa_supplicant( 1168): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1168): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1168): send_and_recv error -67 - cmd 12
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1168): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1168): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1168): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb82d6bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1168):    addr=c0:ff:d4:d3:aa:48
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
E/wpa_supplicant( 1168): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1168): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1168): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1168): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1168): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG70,0
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1168): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): Power_Mode_Type mode = 0
I/wpa_supplicant( 1168): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1168): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1168): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1168): nl80211: if_removed already cleared - ignore event
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1168): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1168): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1168): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1168): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1168): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1168): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1168): Wireless event: cmd=0x8b15 len=20
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  909):    returned true
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/DhcpStateMachine(  909): [RunningState] Stop DHCP
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/PMS     (  909): acquireWL(43aac448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{42822218: PendingIntentRecord{42e4af88 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=787423, Int=0
D/ConnectivityService(  909): Sampling interval elapsed, updating statistics ..
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): Exit handleNetworkDisconnect
D/WifiPerfLock(  909): release()
,D/WifiStateMachine(  909): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): Power_Mode_Type mode = 0
I/wpa_supplicant( 1168): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
I/ActivityManager(  909): Start proc com.htc.cs.dm for service com.htc.cs.dm/com.htc.cs.util.workflow.WorkflowService: pid=4690 uid=10098 gids={50098, 3003, 5012}
D/ConnectivityService(  909): Done.
D/ConnectivityService(  909): Setting timer for 720seconds
V/AlarmManager(  909): sending alarm PendingIntent{42f7fcf8: PendingIntentRecord{43038090 com.htc.cs.dm startService}}, i=com.htc.cs.action.EXECUTE_WORKFLOW, t=1, cnt=1, w=1450445985899, Int=0
D/PMS     (  909): releaseWL(43aac448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  909): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  909): acquireWL(42f78150): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 909 1000 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  909):    returned true
,I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=20203 mDataStallAlarmIntent=null
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  909): doBoolean: SET pno 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): CTRL_IFACE SET 'pno'='1'
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WISPrService( 4140): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4140): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1885/10178)
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
D/UsbnetStateTracker(  909): isAvailable+-
D/UsbnetStateTracker(  909): reconnect
,D/UsbnetStateTracker(  909): isAvailable+-
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1168): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1168): nl80211: Event message available
D/wpa_supplicant( 1168): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
,D/WifiNative-wlan0(  909):    returned true
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/ConnectivityService(  909): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  909): default: reconnect()
D/MDST    (  909): default: setTeardownRequested(false)
D/MDST    (  909): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  909): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  909): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '53 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 53 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
,D/ConnectivityService(  909): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4140): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4140): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '54 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 54 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '55 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 55 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/ConnectivityService(  909): resetConnections(wlan0, 3)
D/libc    (  363): [NET] entry_id:1   entry:0xb7421410  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb7421830  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb7421108  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb7420fd8  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb74215b8  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
I/wpa_supplicant( 1168): wpa_supplicant_scan enter
I/wpa_supplicant( 1168): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1168): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1168): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1168): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1168): nl80211: Event message available
D/wpa_supplicant( 1168): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1885/10178)
D/PMS     (  909): acquireWL(42ec8bd8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
D/ConnectivityService(  909): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,I/QuickSettingWifi( 1123): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  909): acquireWL(445b3510): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  909): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  909): acquireWL(43896028): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4455/10078)
D/ConnectivityService(  909): reportInetCondition for net -1, percentage: 0 by  (1372/10028)
I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/PMS     (  909): releaseWL(445b3510): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  909): releaseWL(42ec8bd8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
,I/QuickSettingWifi( 1123): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiStateMachine(  909): startScan Pid: 909 Uid 1000
D/WifiNative-wlan0(  909): doBoolean: SET pno 0
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1168): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1168): wpa_supplicant_scan enter
D/wpa_supplicant( 1168): nl80211: Event message available
D/wpa_supplicant( 1168): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: SCAN
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
,D/BatSI   (  909): WIFI scan started for: 450a0300 uid:1000
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): wpa_supplicant_scan enter
I/wpa_supplicant( 1168): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1168): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1168): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1168): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1168): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1168): Failed to initiate AP scan
I/wpa_supplicant( 1168): Failed to initiate AP scan, Failed_to_scan_counter:1
,D/WifiNative-wlan0(  909):    returned true
,I/DeviceManagement( 4690): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4690 dbg=false s=true
D/ConnectivityService(  909): mActiveDefaultNetwork: -1
,D/ConnectivityService(  909): handleInetConditionChange: no active default network - ignore
I/DeviceManagement( 4690): WorkflowService: Starting workflow service
,I/DeviceManagement( 4690): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.UpdateWorkflow@42536c18] args=[Bundle[mParcelledData.dataSize=60]]
I/DeviceManagement( 4690): UpdateWorkflow: ==================================================
I/DeviceManagement( 4690): UpdateWorkflow: TTL update...
,I/DeviceManagement( 4690): UpdateWorkflow: ==================================================
,I/DeviceManagement( 4690): ModelRegistry: Loading model meta data from resources...
D/PMS     (  909): releaseWL(43896028): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/DeviceManagement( 4690): SessionStateController: Checking invariants...
,I/DeviceManagement( 4690): BackgroundController: Invariants are unchanged.
,I/DeviceManagement( 4690): SessionStateController: Checking invariants...
,I/DeviceManagement( 4690): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DeviceManagement( 4690): Perf: *** Cache update - start...
I/DeviceManagement( 4690): Perf: *** Enabled app cache update - start...
,I/DeviceManagement( 4690): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 4690): Perf: *** Enabled app cache update - complete: 1 ms
I/DeviceManagement( 4690): Perf: *** Config cache update - start...
I/DeviceManagement( 4690): ConfigCacheController: *** Updating config cache...
,I/DeviceManagement( 4690): ConfigCacheController: *** Updating stale config cache entries...
,W/dalvikvm( 4690): VFY: unable to resolve static method 10661: Lcom/sun/net/httpserver/HttpServer;.create (Ljava/net/InetSocketAddress;I)Lcom/sun/net/httpserver/HttpServer;
W/dalvikvm( 4690): VFY: unable to resolve virtual method 10666: Lcom/sun/net/httpserver/HttpServer;.stop (I)V
,W/dalvikvm( 4690): Link of class 'Lorg/restlet/engine/connector/HttpServerHelper$1;' failed
,W/System.err( 4690): Starting the internal HTTP client
,I/DeviceManagement( 4690): ConfigCacheController: Getting config update from server: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.launcher/versions/b354e2de-d3af-4a3f-b5dc-8239e0d5da72/cid/MDoxNToyMDE1LTEwLTE0VDEwOjI4OjM4LjU4Mlo
,I/DeviceManagement( 4690): DeviceClientResource: Active network...
I/DeviceManagement( 4690):   No active network
,I/DeviceManagement( 4690): DeviceClientResourceController: Network is unavailable: code=1010 description=There is no active network.
,I/DeviceManagement( 4690): BackgroundController: *** Network unavailable!
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (4690/10098)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (4690/10098)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (4690/10098)
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=1, flag=1, pid=4690, uid=10098, userID:0
,I/DeviceManagement( 4690): Perf: *** Config cache update - complete: 175 ms
,I/DeviceManagement( 4690): Perf: *** Cache update - complete: 179 ms
,I/DeviceManagement( 4690): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.UpdateWorkflow@42536c18]
,I/DeviceManagement( 4690): WorkflowService: Stopping workflow service
,D/Process (  909): killProcessQuiet, pid=4317
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4317:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4317
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
D/CaptivePortalTracker(  909): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/CaptivePortalTracker(  909): NoActiveNetworkState
D/GpsLocationProvider(  909): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
,D/Tethering(  909): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  909): bSetPropertyMultiRAB:false
,I/ConnectivityHelper( 1276): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
D/PMS     (  909): acquireWL(43f46be8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/PMS     (  909): releaseWL(43f46be8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1925/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1276/10075)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4455/10078)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1444/10028)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (3858/10154)
I/NetworkMonitor( 3858): type=WIFI subType= reason=null isConnected=false
D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/wpa_supplicant( 1168): wpa_supplicant_scan enter
I/wpa_supplicant( 1168): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1168): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1168): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1168): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1168): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1168): Failed to initiate AP scan
I/wpa_supplicant( 1168): Failed to initiate AP scan, Failed_to_scan_counter:2
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/Tethering(  909): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  909): ipv4Default null
,I/Tethering(  909): No IPv4 upstream interface, giving up.
,D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1885/10178)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (2427/10021)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/PMS     (  909): acquireWL(42faf4a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1230 10028 null
,D/PMS     (  909): acquireWL(44090d68): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1230 10028 null
,D/PMS     (  909): releaseWL(42faf4a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1230/10028),
,D/PMS     (  909): releaseWL(44090d68): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1372): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,D/AutoSetting( 1405): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4455): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4455): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1405): Util - no network available!
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1405/10053)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1405/10053)
I/DeviceManagement( 4690): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.NetworkChangeWorkflow] args=[Bundle[{networkChangeIntent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.htc.cs.dm/.receiver.NetworkChangeReceiver (has extras) }}]]
,D/AutoSetting( 1405): service - onCreate()
,D/AutoSetting( 1405): service - AddressCache: using context: com.htc.Weather
,I/DeviceManagement( 4690): WorkflowService: Starting workflow service
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4497/10151)
I/DeviceManagement( 4690): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@427a33f8] args=[Bundle[mParcelledData.dataSize=900]]
D/LocationManagerService(  909): request 42f720c8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  909): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1405): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1405): service - mHandler: cancel location update
,D/AutoSetting( 1405): service -           changes count: 0
I/DeviceManagement( 4690): NetworkChangeWorkflow: ==================================================
I/DeviceManagement( 4690): NetworkChangeWorkflow: NetworkChange: networkAvailable=false
I/DeviceManagement( 4690): NetworkChangeWorkflow: ==================================================
,I/DeviceManagement( 4690): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@427a33f8]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (4690/10098)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (4690/10098)
I/DeviceManagement( 4690): WorkflowService: Stopping workflow service
,I/dalvikvm-heap( 4117): Grow heap (frag case) to 15.199MB for 1821008-byte allocation
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4117/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4117/10160)
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1885/10178)
,I/dalvikvm-heap( 4117): Grow heap (frag case) to 16.938MB for 1821008-byte allocation
,I/wpa_supplicant( 1168): wpa_supplicant_scan enter
I/wpa_supplicant( 1168): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1168): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1168): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1168): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1168): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1168): Failed to initiate AP scan
,I/wpa_supplicant( 1168): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1168): nl80211: Event message available
D/wpa_supplicant( 1168): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1168): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1168): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1168): nl80211: Survey data missing
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1168): Sorted scan results
I/wpa_supplicant( 1168): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1168): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1168): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1168): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-77
I/wpa_supplicant( 1168): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-87
I/wpa_supplicant( 1168): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
D/wpa_supplicant( 1168): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1168): Add randomness: count=17 entropy=0
D/wpa_supplicant( 1168): Add randomness: count=18 entropy=1
D/wpa_supplicant( 1168): Add randomness: count=19 entropy=2
D/wpa_supplicant( 1168): Add randomness: count=20 entropy=3
D/wpa_supplicant( 1168): Add randomness: count=21 entropy=4
D/wpa_supplicant( 1168): Add randomness: count=22 entropy=5
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1168): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1168): WPS: AP[1] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1168): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1168): wpa_supplicant_pick_network+
I/wpa_supplicant( 1168): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1168): Selecting BSS from priority group 1
I/wpa_supplicant( 1168): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1168): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1168): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1168): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1168): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1168): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1168): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1168): No APs found - clear blacklist and try again
E/wpa_supplicant( 1168): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1168): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1168): Selecting BSS from priority group 1
I/wpa_supplicant( 1168): Recent assoc_freq =, 0 rssi = 0
D/wpa_supplicant( 1168): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1168): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1168): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1168): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1168): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1168): 5: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1168): clear disabled list - type=1
I/wpa_supplicant( 1168): No suitable network found
W/wpa_supplicant( 1168): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1168): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1168): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1168): nl80211: Survey data missing
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1168): Sorted scan results
I/wpa_supplicant( 1168): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1168): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1168): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1168): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-77
I/wpa_supplicant( 1168): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-87
I/wpa_supplicant( 1168): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
D/wpa_supplicant( 1168): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1168): Add randomness: count=23 entropy=6
D/wpa_supplicant( 1168): Add randomness: count=24 entropy=7
D/wpa_supplicant( 1168): Add randomness: count=25 entropy=8
D/wpa_supplicant( 1168): Add randomness: count=26 entropy=9
D/wpa_supplicant( 1168): Add randomness: count=27 entropy=10
D/wpa_supplicant( 1168): Add randomness: count=28 entropy=11
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1168): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1168): WPS: AP[1] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1168): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1168): wpa_supplicant_pick_network+
I/wpa_supplicant( 1168): clear disabled list - type=1
I/wpa_supplicant( 1168): No suitable network found
W/wpa_supplicant( 1168): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1168): State: DISCONNECTED -> INACTIVE
D/WifiNative-wlan0(  909): doBoolean: SET pno 1
D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1168): CTRL_IFACE SET 'pno'='1'
,D/WifiP2pService(  909): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1168): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1168): nl80211: Event message available
,D/wpa_supplicant( 1168): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  909):    returned true
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =INACTIVE
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1168): reply (924) for get BSS: id=1
I/wpa_supplicant( 1168): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1168): freq=2412
I/wpa_supplicant( 1168): level=-51
I/wpa_supplicant( 1168): tsf=0000000109741909
I/wpa_supplicant( 1168): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1168): ssid=NG700
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=7
I/wpa_supplicant( 1168): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1168): freq=5220
I/wpa_supplicant( 1168): level=-49
I/wpa_supplicant( 1168): tsf=0000000109741890
I/wpa_supplicant( 1168): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1168): ssid=NG7005g
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=8
I/wpa_supplicant( 1168): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1168): freq=2412
I/wpa_supplicant( 1168): level=-51
I/wpa_supplicant( 1168): tsf=0000000881292083
I/wpa_supplicant( 1168): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1168): ssid=01ABC
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=9
I/wpa_supplicant( 1168): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1168): freq=2427
I/wpa_supplicant( 1168): level=-73
I/wpa_supplicant( 1168): tsf=0000000881292095
I/wpa_supplicant( 1168): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1168): ssid=Gonzos
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=10
I/wpa_supplicant( 1168): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1168): freq=2437
I/wpa_supplicant( 1168): level=-77
,I/wpa_supplicant( 1168): tsf=0000000881292104
I/wpa_supplicant( 1168): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1168): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=11
I/wpa_supplicant( 1168): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1168): freq=2462
I/wpa_supplicant( 1168): level=-87
I/wpa_supplicant( 1168): tsf=0000000881292114
I/wpa_supplicant( 1168): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1168): ssid=UPC Wi-Free
I/wpa_supplicant( 1168): ====,
I/wpa_supplicant( 1168): id=12
I/wpa_supplicant( 1168): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1168): freq=2437
I/wpa_supplicant( 1168): level=-88
I/wpa_supplicant( 1168): tsf=0000000881292124
I/wpa_supplicant( 1168): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1168): ssid=UPC4688432
I/wpa_supplicant( 1168): ####
D/WifiP2pService(  909): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43a9d6f8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43a9d6f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43a9d6f8 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 2412, timestamp: 109741909, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 109741890, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  909): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -51, frequency: 2412, timestamp: 881292083, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 881292095, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -77, frequency: 2437, timestamp: 881292104, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2462, timestamp: 881292114, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 881292124, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (7) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): add 7 to mScanResults
D/BatSI   (  909): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiStateMachine(  909): startScan Pid: 909 Uid 1000
,D/WifiNative-wlan0(  909): doBoolean: SET pno 0
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1168): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1168): wpa_supplicant_scan enter
I/wpa_supplicant( 1168): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1168): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1168): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1168): nl80211: Event message available
D/wpa_supplicant( 1168): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1168): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: SCAN
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): wpa_supplicant_scan enter
I/wpa_supplicant( 1168): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1168): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1168): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1168): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1168): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1168): Failed to initiate AP scan
,I/wpa_supplicant( 1168): Failed to initiate AP scan, Failed_to_scan_counter:1
,D/WifiNative-wlan0(  909):    returned true
D/BatSI   (  909): WIFI scan started for: 450a0300 uid:1000
,I/wpa_supplicant( 1168): wpa_supplicant_scan enter
I/wpa_supplicant( 1168): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1168): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1168): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1168): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1168): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1168): Failed to initiate AP scan
,I/wpa_supplicant( 1168): Failed to initiate AP scan, Failed_to_scan_counter:2
,I/wpa_supplicant( 1168): wpa_supplicant_scan enter
I/wpa_supplicant( 1168): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1168): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1168): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1168): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1168): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1168): Failed to initiate AP scan
,I/wpa_supplicant( 1168): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1168): nl80211: Event message available
D/wpa_supplicant( 1168): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1168): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1168): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1168): nl80211: Survey data missing
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1168): Sorted scan results
I/wpa_supplicant( 1168): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1168): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1168): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-78
D/wpa_supplicant( 1168): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1168): Add randomness: count=29 entropy=12
D/wpa_supplicant( 1168): Add randomness: count=30 entropy=13
D/wpa_supplicant( 1168): Add randomness: count=31 entropy=14
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1168): WPS: AP[1] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1168): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1168): WPS: AP[3] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1168): wpa_supplicant_pick_network+
I/wpa_supplicant( 1168): Selecting BSS from priority group 1
I/wpa_supplicant( 1168): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1168): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1168): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1168): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1168):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1168):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-51
I/wpa_supplicant( 1168): Start print parameters
I/wpa_supplicant( 1168): wpa_s->wpa_state is 3
I/wpa_supplicant( 1168): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1168): isConcurrentMode() is 0
I/wpa_supplicant( 1168): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1168): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1168): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1168): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1168): wpa_s->reassociate is 0
I/wpa_supplicant( 1168): wpa_s->is_screen_on 0
I/wpa_supplicant( 1168): wpa_s->ifname wlan0
I/wpa_supplicant( 1168): End print parameters
I/wpa_supplicant( 1168): selected network = 13
D/wpa_supplicant( 1168): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb82d84e8  current_ssid=0x0
D/wpa_supplicant( 1168): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1168): supplicant attached completed, ,trigger assoc.
D/wpa_supplicant( 1168): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1168): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1168): check if in concurrent case
I/wpa_supplicant( 1168): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiNative-wlan0(  909): doBoolean: SET pno 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1168): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1168): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1168): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1168): RSN: PMKSA cache search - network_ctx=0xb82d84e8 try_opportunistic=0
D/wpa_supplicant( 1168): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1168): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1168): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1168): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1168): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1168): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1168): nl80211: Unsubscribe mgmt frames handle 0xb82d7718 (mode change)
D/wpa_supplicant( 1168): nl80211: Subscribe to mgmt frames with non-AP handle 0xb82d7718
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Register frame type=0xd0 nl_handle=0xb82d7718
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1168): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1168):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1168):   * freq=2412
D/wpa_supplicant( 1168):   * Auth Type 0
D/wpa_supplicant( 1168):   * WPA Versions 0x2
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1168): nl80211: Connect request send successfully
D/wpa_supplicant( 1168): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1168): ,Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1168): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1168): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =INACTIVE newSupplicantState =ASSOCIATING
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  909):    returned false
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1168): reply (925) for get BSS: id=7
I/wpa_supplicant( 1168): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1168): freq=5220
I/wpa_supplicant( 1168): level=-49
I/wpa_supplicant( 1168): tsf=0000000887362021
I/wpa_supplicant( 1168): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1168): ssid=NG7005g
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=8
I/wpa_supplicant( 1168): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1168): freq=2412
I/wpa_supplicant( 1168): level=-51
I/wpa_supplicant( 1168): tsf=0000000881292083
,I/wpa_supplicant( 1168): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1168): ssid=01ABC
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=9
I/wpa_supplicant( 1168): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1168): freq=2427
I/wpa_supplicant( 1168): level=-73
I/wpa_supplicant( 1168): tsf=0000000881292095
I/wpa_supplicant( 1168): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1168): ssid=Gonzos
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=10
I/wpa_supplicant( 1168): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1168): freq=2437
I/wpa_supplicant( 1168): level=-78
I/wpa_supplicant( 1168): tsf=0000000887362058
I/wpa_supplicant( 1168): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1168): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=11
I/wpa_supplicant( 1168): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1168): freq=2462
I/wpa_supplicant( 1168): level=-87
I/wpa_supplicant( 1168): tsf=0000000881292114
I/wpa_supplicant( 1168): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS],
I/wpa_supplicant( 1168): ssid=UPC Wi-Free
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=12
I/wpa_supplicant( 1168): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1168): freq=2437
I/wpa_supplicant( 1168): level=-88
I/wpa_supplicant( 1168): tsf=0000000881292124
I/wpa_supplicant( 1168): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1168): ssid=UPC4688432
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=13
I/wpa_supplicant( 1168): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1168): freq=2412
I/wpa_supplicant( 1168): level=-51
I/wpa_supplicant( 1168): tsf=0000000887362046
I/wpa_supplicant( 1168): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1168): ssid=NG700
I/wpa_supplicant( 1168): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 887362021, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (7) end of scan result ==
,D/WifiStateMachine(  909): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -51, frequency: 2412, timestamp: 881292083, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 881292095, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -78, frequency: 2437, timestamp: 887362058, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2462, timestamp: 881292114, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 881292124, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 6: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 2412, timestamp: 887362046, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 7 to mScanResults
,D/BatSI   (  909): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/wpa_supplicant( 1168): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1168): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1168): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1168): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1168): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1168): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1168): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1168): nl80211: Event message available
D/wpa_supplicant( 1168): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1168): nl80211: Connect event
D/wpa_supplicant( 1168): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1168): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1168): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1168): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1168): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1168): Add randomness: count=32 entropy=15
I/wpa_supplicant( 1168): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1168): TDLS: Remove peers on association
D/wpa_supplicant( 1168): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1168): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1168): EAPOL: enable timer tick
D/wpa_supplicant( 1168): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1168): htc_wext_set_keepalive +
I/wpa_supplicant( 1168): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1168): getPrivFuncNum +	
I/wpa_supplicant( 1168): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1168): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1168): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1168): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1168): Get randomness: len=32 entropy=16
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  909): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  909): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  909): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  909): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  909): Enter handleAssociatedWithEvent
D/WifiStateMachine(  909): Associated
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString, id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  909): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  909): Exit handleAssociatedWithEvent
D/WifiStateMachine(  909): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/Tethering(  909): interfaceStatusChanged wlan0, false
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
,D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/Tethering(  909): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  909): This record is existed, only update it...
I/wpa_supplicant( 1168): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb82d79f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1168):    addr=c0:ff:d4:d3:aa:48
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  909): updateConnectedAP...
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 11
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1168): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1168): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f68b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1168):    broadcast key
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1168): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,E/wpa_supplicant( 1168): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1168): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1168): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1168): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1168): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1168): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1168): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1168): set send_ind_to_ndc = 0
I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1168): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1168): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1168): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1168): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1168): EAPOL: SUPP_BE entering state SUCCESS,
D/wpa_supplicant( 1168): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1168): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1168): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1168): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1168): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1168): EAPOL authentication completed successfully
I/wpa_supplicant( 1168): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1168): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
,D/wpa_supplicant( 1168): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1168): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
D/Tethering(  909): interfaceStatusChanged wlan0, true
D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
,D/WifiApDatabaseHandler(  909): updateConnectedAP...,
,D/WifiStateMachine(  909): fetchFrequency(), freq = 2412,
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  909): This record is existed, only update it...
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  909): updateConnectedAP...
,I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): mActiveDefaultNetwork: -1
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/WISPrService( 4140): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4140): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1885/10178)
,D/WifiNative-wlan0(  909): doBoolean: SET pno 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): CTRL_IFACE SET 'pno'='0'
,D/WifiNative-wlan0(  909):    returned true
D/DhcpStateMachine(  909): [StoppedState] Start DHCP
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 0
D/WifiStateMachine(  909): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  909): acquireWL(43fbd5a0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 909 1000 null
,D/WifiStateMachine(  909): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): Power_Mode_Type mode = 1
I/wpa_supplicant( 1168): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/wpa_supplicant( 1168): nl80211: Event message available
D/wpa_supplicant( 1168): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1168): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  909):    returned null
E/WifiStateMachine(  909): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  909):    returned null
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4295a1b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4295a1b0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1123): receive.wifiConnect:false wifiAPname:null elapse:1
,I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver packageName:com.htc.cs.dm
,I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver replacing:false
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/SystemReader( 1262): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/PackageBroadcastService( 1230): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.cs.dm
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,I/[PluginManager]RegisterService( 1405): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.cs.dm
,I/[PluginManager]RegisterService( 1405): handle notify Blinkfeed plugin client changed
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,I/PeopleContactsSync( 1230): CP2 sync disabled
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1230, uid=10028, userID:0
,D/PMS     (  909): acquireWL(43dd2e78): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
,I/ActivityManager(  909): Resuming delayed broadcast
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,D/wpa_supplicant( 1168): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1168): EAPOL: disable timer tick
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,D/PMS     (  909): releaseWL(43dd2e78): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
I/PackageManager(  909):   Scheme: "mmsto"
I/IcingCorporaProvider( 2897): Updating corpora: APPS=com.htc.cs.dm, CONTACTS=MAYBE
,D/PhoneApp( 1249): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  909): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  909): acquireWL(438b63b0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4117 10160 null
,D/PMS     (  909): releaseWL(438b63b0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  909): Resuming delayed broadcast
,I/IcingCorporaProvider( 2897): UpdateCorporaTask done [took 88 ms] updated apps [took 88 ms] 
,W/PackageManager(  909): Unable to load service info ResolveInfo{43dd3dc8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  909): start
,D/WifiStateMachine(  909): startScan Pid: 909 Uid 1000
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@425a0e10 +
,I/Prism.WidgetManager( 1276): onLoadItems() +
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,W/asset   ( 1276): Copying FileAsset 0x65eec798 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,E/Prism.WidgetManager( 1276): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1276): onLoadItems() -
,I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@425a0e10 -
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1168): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1168): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  909): releaseWL(43fbd5a0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [4][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
D/WIFI_ICON( 1123): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiStateMachine(  909): gateway: /192.168.1.1
,D/WifiNative-wlan0(  909): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1168): htc_wext_set_keepalive +
I/wpa_supplicant( 1168): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1168): getPrivFuncNum +	
I/wpa_supplicant( 1168): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1168): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1168): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1168): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1168): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  909): VerifyingLinkState enter
,D/WifiStateMachine(  909): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiNative-wlan0(  909): doBoolean: SCAN TYPE=ONLY
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1168): wpa_supplicant_scan enter
I/wpa_supplicant( 1168): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1168): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1168): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1168): nl80211: Event message available
,D/wpa_supplicant( 1168): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  909):    returned true
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/BatSI   (  909): WIFI scan started for: 450a0300 uid:1000
D/WifiStateMachine(  909): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  909): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -52, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1123): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  909): WAN detection
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  909): Provision feature enable=false
V/NetworkPolicy(  909): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  909): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  909): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  909): default: teardown()
D/MDST    (  909): default: setTeardownRequested(true)
D/MDST    (  909): default: setEnableApn apnType =default , enable=false
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/MDST    (  909): default: setTeardownRequested(true)
D/ConnectivityService(  909): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1885/10178)
E/ConnectivityService(  909): Unexpected mtu value: android.net.wifi.WifiStateTracker@42e407d0
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4140): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1123): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1123): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ConnectivityService(  909): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,I/QuickSettingWifi( 1123): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/PhoneApp( 1249): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1249): -- N1 =0
,D/PhoneApp( 1249): -- N2 =0
,D/PhoneApp( 1249): -- N3 =0
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
E/NetdConnector(  909): NDC Command {63 interface route add wlan0 default 192.168.1.0 24 0.0.0.0} took too long (794ms)
D/ConnectivityService(  909): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/WifiStateMachine(  909): syncGetConfiguredNetworks
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  909): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  909): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  909): acquireWL(43fb0f58): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/ConnectivityService(  909): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4455/10078)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WirelessDisplayService(  909): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  909):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,D/PMS     (  909): acquireWL(4306af70): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1230 10028 null
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  909): releaseWL(43fb0f58): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1168): Change stage from stage0 to stage3
I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
D/PMS     (  909): acquireWL(42e831d0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1230 10028 null
D/PMS     (  909): releaseWL(4306af70): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,I/CheckinService( 1230): Preparing to send checkin request
,I/EventLogService( 1230): Accumulating logs since 1450445336905
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 1230): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1230): Using GMS GoogleHttpClient
D/ConnectivityService(  909): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (1230/10028)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getNetworkInfo networkType=0 called by com.google.android.gms (1230/10028)
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PMS     (  909): releaseWL(42f78150): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/CheckinRequestBuilder( 1230): awaiting user notification for token
,I/RemoteViews( 1123): com.google.android.gms (false,0)
D/ConnectivityService(  909): NetTransition Wakelock for ConnectedState released by timeout
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{42503078 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.google.android.gms 1 8 3 12
,I/Adreno-EGL( 4565): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4565): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4565): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4565): Local Branch: 
I/Adreno-EGL( 4565): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4565): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4565):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4565/10028)
,W/Settings( 4565): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4565): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4565): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4565): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4565): Local Branch: 
I/Adreno-EGL( 4565): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4565): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4565):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4565): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4565): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4565): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4565): Local Branch: 
I/Adreno-EGL( 4565): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4565): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4565):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/CaptivePortalTracker(  909): NoActiveNetworkState
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (3858/10154)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,I/NetworkMonitor( 3858): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
I/ConnectivityHelper( 1276): [onReceive] WIFI(1): CONNECTED
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
V/Tethering(  909): bSetPropertyMultiRAB:false
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1276/10075)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4455/10078)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1444/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  909): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  909): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  909): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  909): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  909): Found interface wlan0
,D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
I/acms    ( 1925): Checking Certificates
I/acms    ( 1925): Checking Developer Certificates
I/acms    ( 1925): Checking Application Certificates
I/acms    ( 1925): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1925): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1925): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1925): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1925): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1925): Updating next query delay: 75600000
I/mlserverapp( 1925): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1925): cancelACMSProgrammedChecks
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1925/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1885/10178)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/PMS     (  909): acquireWL(42655f88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(444bd078): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (2427/10021)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4426/10026)
,D/PMS     (  909): acquireWL(44ac1578): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1230 10028 null
,I/CheckinTask( 1230): Sending checkin request (8963 bytes)
,D/PMS     (  909): releaseWL(44ac1578): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/libc    ( 1230): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1230): [NET] getaddrinfo-,err=8
D/libc    ( 1230): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1230): [NET] getaddrinfo-, 1
D/libc    ( 1230): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =a27b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/GCM     ( 1372): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  909): acquireWL(44048650): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1372 10028 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1372): [NET] getaddrinfo-,err=8
D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1372): [NET] getaddrinfo-, 1
D/libc    ( 1372): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =1664 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1405): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/MobileConnectivityChangeReceiver( 4455): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4455): onReceive CONNECTIVITY_CHANGE networkType=1
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1405/10053)
D/AutoSetting( 1405): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
I/DeviceManagement( 4690): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.NetworkChangeWorkflow] args=[Bundle[{networkChangeIntent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.htc.cs.dm/.receiver.NetworkChangeReceiver (has extras) }}]]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/AutoSetting( 1405): service - onStartCommand() screen is off, don't request location
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1405/10053)
I/DeviceManagement( 4690): WorkflowService: Starting workflow service
D/AutoSetting( 1405): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1405): service - onStartCommand() check timezone in 30000
I/DeviceManagement( 4690): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@427a33f8] args=[Bundle[mParcelledData.dataSize=804]]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4497/10151)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (4690/10098)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
I/DeviceManagement( 4690): NetworkChangeWorkflow: ==================================================
I/DeviceManagement( 4690): NetworkChangeWorkflow: NetworkChange: networkAvailable=true
I/DeviceManagement( 4690): NetworkChangeWorkflow: ==================================================
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/DeviceManagement( 4690): SessionStateController: Checking invariants...
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (4690/10098)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): acquireWL(43c20df0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(43c20df0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4117/10160)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4117/10160)
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
D/ConnectivityService(  909): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1885/10178)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
I/DeviceManagement( 4690): BackgroundController: Invariants are unchanged.
I/DeviceManagement( 4690): Perf: *** Cache update - start...
I/DeviceManagement( 4690): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 4690): EnabledAppController: *** Updating enabled app database...
,I/DeviceManagement( 4690): Perf: *** Enabled app cache update - complete: 1 ms
I/DeviceManagement( 4690): Perf: *** Config cache update - start...
I/DeviceManagement( 4690): ConfigCacheController: *** Updating config cache...
,I/DeviceManagement( 4690): ConfigCacheController: *** Updating stale config cache entries...
D/PMS     (  909): acquireWL(43724f58): PARTIAL_WAKE_LOCK  *sync*/com.htc.showme/com.htc.showme/***** 0x1 909 1000 WorkSource{10082}
,I/ActivityManager(  909): Start proc com.htc.showme for service com.htc.showme/.sync.SyncService: pid=4784 uid=10082 gids={50082, 3003, 5012, 1028, 1015}
,D/PMS     (  909): acquireWL(43a55da0): PARTIAL_WAKE_LOCK  *sync*/gmail-ls/com.google/***** 0x1 909 1000 WorkSource{10107}
I/DeviceManagement( 4690): ConfigCacheController: Getting config update from server: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.launcher/versions/b354e2de-d3af-4a3f-b5dc-8239e0d5da72/cid/MDoxNToyMDE1LTEwLTE0VDEwOjI4OjM4LjU4Mlo
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  909): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=4796 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,I/DeviceManagement( 4690): DeviceClientResource: Active network...
I/DeviceManagement( 4690):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  909): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (4690/10098)
D/PMS     (  909): releaseWL(444bd078): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  909): releaseWL(42655f88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (4690/10098)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(44a2f6a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (4690/10098)
D/BuildInfo( 4690): Created new instance: com.htc.cs.lib.hms.BuildInfo@4280bb78
I/DeviceManagement( 4690): Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_,supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/libc    ( 4690): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4690): [NET] getaddrinfo-, 1
D/libc    ( 4690): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4690): [NET] getaddrinfo_proxy-, success
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/wpa_supplicant( 1168): nl80211: Event message available
D/wpa_supplicant( 1168): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1168): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1168): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1168): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1168): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1168): nl80211: Survey data missing
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1168): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1168): Sorted scan results
I/wpa_supplicant( 1168): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1168): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant(, 1168): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-77
D/wpa_supplicant( 1168): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1168): Add randomness: count=33 entropy=0
D/wpa_supplicant( 1168): Add randomness: count=34 entropy=1
D/wpa_supplicant( 1168): Add randomness: count=35 entropy=2
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1168): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1168): reply (382) for get BSS: id=7
I/wpa_supplicant( 1168): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1168): freq=5220
I/wpa_supplicant( 1168): level=-49
I/wpa_supplicant( 1168): tsf=0000000894051967
I/wpa_supplicant( 1168): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1168): ssid=NG7005g
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=10
I/wpa_supplicant( 1168): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1168): freq=2437
I/wpa_supplicant( 1168): level=-77
I/wpa_supplicant( 1168): tsf=0000000894051989
I/wpa_supplicant( 1168): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1168): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1168): ====
I/wpa_supplicant( 1168): id=13
I/wpa_supplicant( 1168): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1168): freq=2412
I/wpa_supplicant( 1168): level=-55
I/wpa_supplicant( 1168): tsf=0000000894051983
I/wpa_supplicant( 1168): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1168): ssid=NG700
I/wpa_supplicant( 1168): ####
D/WifiStateMachine(  909): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 894051967, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -77, frequency: 2437, timestamp: 894051989, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 894051983, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 3 to mScanResults
D/WirelessDisplayService(  909): getDiscoveryDongleList
V/ScoreHelper(  909): Only print Top 10 in ApScanList
V/ScoreHelper(  909):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  909):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  909):  + ScoreResult:  81, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  8 [-77], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  909):  + computeScore(NG700): 1
D/WifiStateMachine(  909): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (3) end of scan result ==
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/BatSI   (  909): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [2][0][0]
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1168): Change stage from stage3 to stage0
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): releaseWL(44a2f6a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(44548d50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/PMS     (  909): releaseWL(44548d50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,I/[AppShowMeDebug]SyncAdapter( 4784): onPerformSync() 
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.showme (4784/10082)
I/[AppShowMeDebug]CheckUpdateTask( 4784): check and download urlSKUBased = http://showme.htctouch.com/prod/LU15A_CTH=401/; urlDeviceBased = http://showme.htctouch.com/prod/LU15A_CTH/; urlSKUTestDeviceBased = http://showme-test.htc.com.tw/testpub/LU15A_CTH=401/; urlTestDeviceBased = http://showme-test.htc.com.tw/testpub/LU15A_CTH/
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 11
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1372): [NET] getaddrinfo_proxy-, success
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 232
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4690): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4690): [NET] getaddrinfo-,err=8
D/libc    ( 4690): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4690): [NET] getaddrinfo-, 1
D/libc    ( 4690): [NET] getaddrinfo_proxy+
D/libc    ( 1230): [NET] getaddrinfo_proxy-, success
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =2e7b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,W/GAV2    ( 4796): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/libc    ( 1230): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1230): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=204
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4690): [NET] getaddrinfo_proxy-, success
D/libc    ( 4784): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 4
D/libc    ( 4784): [NET] getaddrinfo-,err=8
D/libc    ( 4784): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 1024
D/libc    ( 4784): [NET] getaddrinfo-, 1
,D/libc    ( 4784): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =2fdb +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  909): acquireWL(44a46758): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/PMS     (  909): releaseWL(44a46758): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  909): acquireWL(43f93bc8): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
,D/PMS     (  909): releaseWL(43f93bc8): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1372): [NET] getaddrinfo-,err=8
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  909): acquireWL(43018db0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/PMS     (  909): releaseWL(43018db0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  909): acquireWL(440aae48): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
,D/PMS     (  909): releaseWL(440aae48): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/Gmail   ( 4796): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=246
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=6
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4784): [NET] getaddrinfo_proxy-, success
,I/Gmail   ( 4796): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4796): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4796): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gm (4796/10107)
,I/Gmail   ( 4796): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 5334, normalSync: true
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com mail
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1372): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1372): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1372): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1372): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1372): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1123): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{426b1130 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.google.android.gms 2 12 3 12
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,D/GCM     ( 1372): Connected
D/PMS     (  909): acquireWL(430d33d0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com mail
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PMS     (  909): releaseWL(44048650): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  909): releaseWL(430d33d0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  909): acquireWL(42f26a58): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
,W/GLSActivity( 1372): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1372): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1372): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1372): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1372): 	at dalvik.system.NativeStart.run(Native Method)
D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1123): com.google.android.gms (false,0)
,D/GCM     ( 1372): Message class mpf
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{4299a2d0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.google.android.gms 1 9 4 12
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  909): releaseWL(42f26a58): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  909): acquireWL(43a99c48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/PMS     (  909): releaseWL(43a99c48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(44a8cd18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/SyncManager(  909): failed sync operation  u0 (com.google), gmail-ls, PERIODIC, latestRunTime 893821, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  909): not retrying sync operation because the error is a hard error:  u0 (com.google), gmail-ls, PERIODIC, latestRunTime 894596, reason: Periodic
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(43a55da0): PARTIAL_WAKE_LOCK  *sync*/gmail-ls/com.google/***** 0x1 WorkSource{10107}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1444/10028)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=28 [35][10][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168),: Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): acquireWL(44658610): PARTIAL_WAKE_LOCK  *sync*/subscribedfeeds/com.google/***** 0x1 909 1000 WorkSource{10028}
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/ExternalAccountType( 1335): Unsupported attribute readOnly
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(44a8cd18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(436479a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/,WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(436479a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(4496ea90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(4496ea90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 4784): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 4
D/libc    ( 4784): [NET] getaddrinfo-,err=8
D/libc    ( 4784): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 1024
D/libc    ( 4784): [NET] getaddrinfo-, 1
D/libc    ( 4784): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x73686f776d652e),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =de0e +++++
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/libc    (  363): [NET]res_queryN: exit 3, ancount=6
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
D/libc    ( 4784): [NET] getaddrinfo_proxy-, success
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0( , 909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
W/GLSUser ( 1372): GoogleAccountDataService.getToken()
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/,wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com mail
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNa,tive-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/DeviceManagement( 4690): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4690): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 4690): DeviceClientResourceController: handleDirectives: []
W/dalvikvm( 4690): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;)
,W/dalvikvm( 4690): VFY: unable to resolve virtual method 8166: Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;.schemaFor (Ljava/lang/Class;)Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;
E/dalvikvm( 4690): Could not find class 'com.fasterxml.jackson.dataformat.smile.SmileFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 4690): VFY: unable to resolve new-instance 808 (Lcom/fasterxml/jackson/dataformat/smile/SmileFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
,W/dalvikvm( 4690): VFY: unable to resolve static method 11799: Ljavax/xml/stream/XMLInputFactory;.newFactory ()Ljavax/xml/stream/XMLInputFactory;
E/dalvikvm( 4690): Could not find class 'com.fasterxml.jackson.dataformat.yaml.YAMLFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 4690): VFY: unable to resolve new-instance 811 (Lcom/fasterxml/jackson/dataformat/yaml/YAMLFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4690): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 4690): VFY: unable to resolve new-instance 805 (Lcom/fasterxml/jackson/dataformat/csv/CsvFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4690): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectReader
W/dalvikvm( 4690): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4690): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectWriter
W/dalvikvm( 4690): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4690): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.getCsvSchema
W/dalvikvm( 4690): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
W/dalvikvm( 4690): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
,W/dalvikvm( 4690): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
I/System.out( 4690): isCompatible false
,I/System.out( 4690): createObjectMapper
I/System.out( 4690): isCompatible false
I/System.out( 4690): isCompatible false
I/System.out( 4690): isCompatible false
I/System.out( 4690): isCompatible false
I/System.out( 4690): isCompatible false
I/System.out( 4690): isCompatible false
,I/System.out( 4690): isCompatible false
,W/GLSActivity( 1372): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1372): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1372): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1372): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1372): 	at dalvik.system.NativeStart.run(Native Method)
,D/PMS     (  909): acquireWL(44d3c3d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,I/RemoteViews( 1123): com.google.android.gms (false,0)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(44ab7878): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/PMS     (  909): releaseWL(44d3c3d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  909): releaseWL(44658610): PARTIAL_WAKE_LOCK  *sync*/subscribedfeeds/com.google/***** 0x1 WorkSource{10028}
D/SyncManager(  909): failed sync operation  u0 (com.google), subscribedfeeds, PERIODIC, latestRunTime 893825, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager(  909): not retrying sync operation because the error is a hard error:  u0 (com.google), subscribedfeeds, PERIODIC, latestRunTime 894904, reason: Periodic
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{429b6b68 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1444/10028)
W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [4][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/RemoteViews.Performance( 1123): com.google.android.gms 1 17 6 12
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug ,wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =3801 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/ExternalAccountType( 1335): Unsupported attribute readOnly
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplican,t( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/PMS     (  909): acquireWL(438700a8): PARTIAL_WAKE_LOCK  *sync*/com.android.calendar/com.google/***** 0x1 909 1000 WorkSource{10108}
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  909): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=4847 uid=10108 gids={50108, 3003, 5012}
D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (1230/10028)
D/ConnectivityService(  909): getNetworkInfo networkType=0 called by com.google.android.gms (1230/10028)
D/PMS     (  909): releaseWL(44ab7878): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(4300a4e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/DeviceManagement( 4690): ConfigCacheController: Getting config update from server: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.pushclient/versions/c0b07203-b6aa-4cf1-944f-7ae27c536a6b/cid/MDoxOjIwMTMtMTItMjBUMDk6MzY6NTguNjI2Wg
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (4690/10098)
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
I/DeviceManagement( 4690): DeviceClientResource: Active network...
I/DeviceManagement( 4690):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
D/WifiWatchdogStateMachine(  909): Find DNS Address www.htc.com/23.59.123.86
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (4690/10098)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (4690/10098)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
I/[AppShowMeDebug]SyncAdapter( 4784): Sync task finished
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 4690): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4690): [NET] getaddrinfo-, 1
D/libc    ( 4690): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4690): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/libc    ( 4690): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/libc    ( 4690): [NET] getaddrinfo-,err=8
D/libc    ( 4690): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4690): [NET] getaddrinfo-, 1
D/libc    ( 4690): [NET] getaddrinfo_proxy+
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =734c +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4690): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
W/AbstractGoogleClient( 4847): Application name is not set. Call Builder#setApplicationName.
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/PMS     (  909): releaseWL(4300a4e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(44a26880): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
W/GLSUser ( 1372): GoogleAccountDataService.getToken()
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(43724f58): PARTIAL_WAKE_LOCK  *sync*/com.htc.showme/com.htc.showme/***** 0x1 WorkSource{10082}
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd ,1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,W/CheckinRequestBuilder( 1230): awaiting user notification for token
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/PMS     (  909): acquireWL(4384dc80): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts/com.google/***** 0x1 909 1000 WorkSource{10028}
D/PMS     (  909): releaseWL(44a26880): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(430d2fb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1123): com.google.android.gms (false,0)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/PMS     (  909): releaseWL(430d2fb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(43c601c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(43c601c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{429ced18 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
I/RemoteViews.Performance( 1123): com.google.android.gms 2 10 3 12
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/CheckinTask( 1230): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
W/GoogleHttpClient( 1230): Unable to close GMS GoogleHttpClient
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_,POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  909): releaseWL(42e831d0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1230): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@4266d6e0 that was originally bound here
E/ActivityThread( 1230): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@4266d6e0 that was originally bound here
E/ActivityThread( 1230): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1230): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1230): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1230): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1230): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1230): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1230): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1230): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1230): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1230): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1230): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1230): 	at bks.a(SourceFile:298)
E/ActivityThread( 1230): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1230): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1230): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1230): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1372): GCM config loaded
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com cp
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1372): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1372): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1372): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1372): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1372): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1123): com.google.android.gms (false,0)
,D/ContactsSyncAdapter( 1372): innerSync failed
D/ContactsSyncAdapter( 1372): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1372): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 1372): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 1372): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 1372): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 1372): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 1372): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1372): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
D/ContactsSyncAdapter( 1372): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 1372): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
D/ContactsSyncAdapter( 1372): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 1372): 	at android.os.Binder.execTransact(Binder.java:412)
D/ContactsSyncAdapter( 1372): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{42a5b218 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.google.android.gms 1 8 3 12
,D/SyncManager(  909): failed sync operation  u0 (com.google), com.android.contacts, PERIODIC, latestRunTime 893837, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(44541b28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(4384dc80): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts/com.google/***** 0x1 WorkSource{10028}
D/SyncManager(  909): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts, PERIODIC, latestRunTime 895280, reason: Periodic
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1444/10028)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): s,end_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
W/GLSUser ( 1372): GoogleAccountDataService.getToken()
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): acquireWL(4499eda8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.people/com.google/***** 0x1 909 1000 WorkSource{10028}
D/PMS     (  909): releaseWL(44541b28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(44a89aa8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/ExternalAccountType( 1335): Unsupported attribute readOnly
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/calendar
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{43fa0cf8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(44a89aa8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(4385dbf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(4385dbf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
I/PeopleSync( 1230): onPerformSync() [5005f081]
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/RemoteViews( 1123): com.google.android.gms (false,0)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/CalendarSyncAdapter( 4847): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 4847): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 4847): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 4847): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 4847): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:836)
E/CalendarSyncAdapter( 4847): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:412)
E/CalendarSyncAdapter( 4847): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:345)
E/CalendarSyncAdapter( 4847): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:463)
E/CalendarSyncAdapter( 4847): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:1510)
E/CalendarSyncAdapter( 4847): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1024)
E/CalendarSyncAdapter( 4847): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:906)
E/CalendarSyncAdapter( 4847): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:430)
E/CalendarSyncAdapter( 4847): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:335)
E/CalendarSyncAdapter( 4847): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 4847): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 4847): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 4847): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 4847): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 4847): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 4847): 	... 12 more
E/wpa_supplicant( ,1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{42a83ed8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/DeviceManagement( 4690): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4690): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4690): DeviceClientResourceController: handleDirectives: []
I/System.out( 4690): isCompatible false
I/System.out( 4690): createObjectMapper
I/System.out( 4690): isCompatible false
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
I/System.out( 4690): isCompatible false
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
I/System.out( 4690): isCompatible false
I/System.out( 4690): isCompatible false
I/System.out( 4690): isCompatible false
I/System.out( 4690): isCompatible false
I/System.out( 4690): isCompatible false
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(4454ae20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/SyncManager(  909): failed sync operation  u0 (com.google), com.android.calendar, PERIODIC, latestRunTime 893829, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager(  909): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.calendar, PERIODIC, latestRunTime 895417, reason: Periodic
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(438700a8): PARTIAL_WAKE_LOCK  *sync*/com.android.calendar/com.google/***** 0x1 WorkSource{10108}
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/RemoteViews.Performance( 1123): com.google.android.gms 2 23 4 12
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1444/10028)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/ExternalAccountType( 1335): Unsupported attribute readOnly
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
D/PMS     (  909): acquireWL(431c6f68): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.plus.action/com.google/***** 0x1 909 1000 WorkSource{10028}
D/PMS     (  909): releaseWL(4454ae20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(44a515a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=w,lan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
I/DeviceManagement( 4690): ConfigCacheController: Getting config update from server: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.backup/versions/f14176fb-9327-4d08-a3c6-5749fcce54ec/cid/MDo0OjIwMTUtMDQtMjNUMjA6NTQ6MDcuMzczWg
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/PeopleDatabaseHelper( 1230): cleanUpNonGplusAccounts done.
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): releaseWL(44a515a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,I/DeviceManagement( 4690): DeviceClientResource: Active network...
I/DeviceManagement( 4690):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (4690/10098)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (4690/10098)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.cs.dm (4690/10098)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/libc    ( 4690): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4690): [NET] getaddrinfo-, 1
D/libc    ( 4690): [NET] getaddrinfo_proxy+
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    ( 4690): [NET] getaddrinfo_proxy-, success
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
D/libc    ( 4690): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    ( 4690): [NET] getaddrinfo-,err=8
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 4690): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4690): [NET] getaddrinfo-, 1
D/libc    ( 4690): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =1210 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4690): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error, 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4472dff0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,I/PeopleSync( 1230): Setting subscription: result=true [5005f081]
D/PMS     (  909): releaseWL(4472dff0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/PeopleSync( 1230): Starting sync, feed=null [5005f081]
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(44620468): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(431c6f68): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.plus.action/com.google/***** 0x1 WorkSource{10028}
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=50 [4][2][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  909): acquireWL(44256bd0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.videos.sync/com.google/***** 0x1 909 1000 WorkSource{10165}
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_suppli,cant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  909): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=4878 uid=10165 gids={50165, 3003, 5012, 1028, 1015, 3002}
,D/PMS     (  909): releaseWL(44620468): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,I/PeopleSync( 1230): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/PeopleSync( 1230): Sync finished, successful=false, took 58ms
,I/PeopleSync( 1230): Cannot authenticate [5005f081]
I/PeopleSync( 1230): arx: BadAuthentication
I/PeopleSync( 1230): 	at arj.a(SourceFile:411)
I/PeopleSync( 1230): 	at byt.b(SourceFile:91)
I/PeopleSync( 1230): 	at bxr.b(SourceFile:334)
I/PeopleSync( 1230): 	at byd.b(SourceFile:355)
I/PeopleSync( 1230): 	at byd.a(SourceFile:325)
I/PeopleSync( 1230): 	at byd.a(SourceFile:304)
I/PeopleSync( 1230): 	at iur.a(SourceFile:460)
I/PeopleSync( 1230): 	at hoi.e(SourceFile:905)
I/PeopleSync( 1230): 	at hoi.a(SourceFile:220)
I/PeopleSync( 1230): 	at hoa.a(SourceFile:251)
I/PeopleSync( 1230): 	at hoa.a(SourceFile:170)
I/PeopleSync( 1230): 	at hoa.onPerformSync(SourceFile:89)
I/PeopleSync( 1230): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/PeopleSync( 1230): Sync finished, duration: 223 [5005f081]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(43a7e098): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/ConnectivityService(  909): getNetworkInfo networkType=0 called by com.google.android.videos (4878/10165)
,D/PMS     (  909): releaseWL(4499eda8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.people/com.google/***** 0x1 WorkSource{10028}
,D/Process (  909): killProcessQuiet, pid=4403
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/SyncManager(  909): failed sync operation  u0 (com.google), com.google.android.gms.people, PERIODIC, latestRunTime 893845, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  909): not retrying sync operation because the error is a hard error:  u0 (com.google), com.google.android.gms.people, PERIODIC, latestRunTime 895894, reason: Periodic
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  909): Killing 4403:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1444/10028)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/DeviceManagement( 4690): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4690): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4690): DeviceClientResourceController: handleDirectives: []
I/System.out( 4690): isCompatible false
I/System.out( 4690): createObjectMapper
,I/System.out( 4690): isCompatible false
I/System.out( 4690): isCompatible false
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
I/System.out( 4690): isCompatible false
I/System.out( 4690): isCompatible false
I/System.out( 4690): isCompatible false
I/System.out( 4690): isCompatible false
,I/System.out( 4690): isCompatible false
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 4403
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  909): acquireWL(44ab9590): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.cloudprint.cloudprintprovider/com.google/***** 0x1 909 1000 WorkSource{10097}
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  909): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=4896 uid=10097 gids={50097, 3003, 5012, 1028}
D/PMS     (  909): releaseWL(43a7e098): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(44312d38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
E/ExternalAccountType( 1335): Unsupported attribute readOnly
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I,/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/DeviceManagement( 4690): ConfigCacheController: *** Update config cache: updating 3 entries...
I/DeviceManagement( 4690): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, statusCode=0, authCode=0>
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/PlayMovies( 4878): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  909): releaseWL(44312d38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,V/com.google.android.apps.common.multidex.Tracer( 4896): Checking if extracted archive /data/data/com.google.android.apps.cloudprint/files/secondary0.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4896): Extracted file last modified: Aug 26, 2015 14:34:58.0
V/com.google.android.apps.common.multidex.Tracer( 4896): Package last updated: Mar 27, 2015 8:20:30.0
,V/com.google.android.apps.common.multidex.Tracer( 4896): Checking if extracted archive /data/data/com.google.android.apps.cloudprint/files/secondary1.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4896): Extracted file last modified: Aug 26, 2015 14:34:58.0
V/com.google.android.apps.common.multidex.Tracer( 4896): Package last updated: Mar 27, 2015 8:20:30.0
V/com.google.android.apps.common.multidex.Tracer( 4896): Attempting to patch the classloader using the following patchers [com.google.android.apps.common.multidex.KlpClassLoaderExtender@42523670, com.google.android.apps.common.multidex.IcsClassLoaderExtender@425243e0, com.google.android.apps.common.multidex.PreIcsClassLoaderExtender@42524738]
,V/com.google.android.apps.common.multidex.Tracer( 4896): Trying com.google.android.apps.common.multidex.KlpClassLoaderExtender@42523670.
,V/com.google.android.apps.common.multidex.Tracer( 4896): Patching was successful.
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42759150): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(42759150): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/WifiDisplayAdapter(  909): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  909):     Client/Owner: Client
D/WifiDisplayAdapter(  909):     GroupId: 
D/WifiDisplayAdapter(  909):     Passphrase: 
D/WifiDisplayAdapter(  909):     SessionId: 0
D/WifiDisplayAdapter(  909):     IP Address: }
,I/ActivityManager(  909): Start proc com.google.android.apps.cloudprint for content provider com.google.android.apps.cloudprint/.printdialog.database.CloudPrintContentProvider: pid=4919 uid=10097 gids={50097, 3003, 5012, 1028}
,D/MediaRouterService(  909): Client com.google.android.videos (pid 4878): Registered
,I/DeviceManagement( 4690): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, statusCode=0, authCode=0>
,D/WifiDisplayAdapter(  909): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  909):     Client/Owner: Client
D/WifiDisplayAdapter(  909):     GroupId: 
D/WifiDisplayAdapter(  909):     Passphrase: 
D/WifiDisplayAdapter(  909):     SessionId: 0
D/WifiDisplayAdapter(  909):     IP Address: }
I/MediaRouter( 4878): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.videos (4878/10165)
D/PlayMovies( 4878): MediaRouteManager.maybeRestoreRoute:188 sessionRestore routeId: 
,D/PlayMovies( 4878): MediaRouteManager.onRouteSelected:149 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,V/com.google.android.apps.common.multidex.Tracer( 4919): Checking if extracted archive /data/user/0/com.google.android.apps.cloudprint/files/secondary0.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4919): Extracted file last modified: Aug 26, 2015 14:34:58.0
V/com.google.android.apps.common.multidex.Tracer( 4919): Package last updated: Mar 27, 2015 8:20:30.0
,V/com.google.android.apps.common.multidex.Tracer( 4919): Checking if extracted archive /data/user/0/com.google.android.apps.cloudprint/files/secondary1.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4919): Extracted file last modified: Aug 26, 2015 14:34:58.0
V/com.google.android.apps.common.multidex.Tracer( 4919): Package last updated: Mar 27, 2015 8:20:30.0
V/com.google.android.apps.common.multidex.Tracer( 4919): Attempting to patch the classloader using the following patchers [com.google.android.apps.common.multidex.KlpClassLoaderExtender@42527af0, com.google.android.apps.common.multidex.IcsClassLoaderExtender@42528860, com.google.android.apps.common.multidex.PreIcsClassLoaderExtender@42528bb8]
,V/com.google.android.apps.common.multidex.Tracer( 4919): Trying com.google.android.apps.common.multidex.KlpClassLoaderExtender@42527af0.
,V/com.google.android.apps.common.multidex.Tracer( 4919): Patching was successful.
,D/PlayMovies( 4878): TransferService.onCreate:52 creating transfer service
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(43a8a598): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/PMS     (  909): releaseWL(43a8a598): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.videos (4878/10165)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.videos (4878/10165)
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=com.google.android.videos.pinning.TransferService$Receiver, state=1, flag=1, pid=4878, uid=10165, userID:0
,I/DeviceManagement( 4690): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, statusCode=0, authCode=0>
,D/MediaRouter( 4878): getSelectedRoute
,D/PlayMovies( 4878): MediaRouteManager.onRouteAdded:140 new route added android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE
,D/PlayMovies( 4878): MediaRouteManager.onRouteSelected:149 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4878): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.videos/files/Movies
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.videos (4878/10165)
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/PMS     (  909): acquireWL(44a90d48): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.videos (4878/10165)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.videos (4878/10165)
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=com.google.android.videos.pinning.TransferService$Receiver, state=2, flag=1, pid=4878, uid=10165, userID:0
,I/DeviceManagement( 4690): ConfigCacheController: No changes need to be broadcasted.
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,I/DeviceManagement( 4690): AlarmController: Scheduling TTL alarm for: 2015.12.19 at 14:38:44.560 CET (due to: com.htc.aurora)
D/PMS     (  909): releaseWL(44a90d48): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=4690, uid=10098, userID:0
,I/DeviceManagement( 4690): Perf: *** Config cache update - complete: 2226 ms
I/DeviceManagement( 4690): Perf: *** Cache update - complete: 2228 ms
,I/DeviceManagement( 4690): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@427a33f8]
,I/DeviceManagement( 4690): WorkflowService: Stopping workflow service
,D/PMS     (  909): acquireWL(446004d0): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/WifiStateMachine(  909): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PMS     (  909): releaseWL(446004d0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(44d3c3d0): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
,I/RemoteViews( 1123): com.google.android.gms (false,0)
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4896): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{42631e08 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    ( 4896): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4896): [NET] getaddrinfo-,err=8
D/libc    ( 4896): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4896): [NET] getaddrinfo-, 1
,D/libc    ( 4896): [NET] getaddrinfo_proxy+
D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews.Performance( 1123): com.google.android.gms 1 7 3 12
D/libc    (  363): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =16c8 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,E/PlayMovies( 4878): GmsAccountManagerWrapper.blockingGetAuthTokenInternal:70 Cannot get user auth
E/PlayMovies( 4878): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 4878): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/PlayMovies( 4878): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/PlayMovies( 4878): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:60)
E/PlayMovies( 4878): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingGetAuthToken(AccountManagerWrapper.java:183)
E/PlayMovies( 4878): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingAuthenticate(AccountManagerWrapper.java:162)
E/PlayMovies( 4878): 	at com.google.android.videos.store.SyncService$SyncAdapter.onPerformSync(SyncService.java:223)
E/PlayMovies( 4878): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayMovies( 4878): AccountManagerWrapper.blockingAuthenticate:165 Authentication failed
E/PlayMovies( 4878): com.google.android.videos.accounts.AccountManagerWrapper$AuthTokenException: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 4878): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:71)
E/PlayMovies( 4878): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingGetAuthToken(AccountManagerWrapper.java:183)
E/PlayMovies( 4878): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingAuthenticate(AccountManagerWrapper.java:162)
E/PlayMovies( 4878): 	at com.google.android.videos.store.SyncService$SyncAdapter.onPerformSync(SyncService.java:223)
E/PlayMovies( 4878): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/PlayMovies( 4878): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 4878): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/PlayMovies( 4878): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/PlayMovies( 4878): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:60)
E/PlayMovies( 4878): 	... 4 more
,I/RemoteViews( 1123): com.google.android.gms (false,0)
,I/RemoteViews.Performance( 1123): com.google.android.gms 1 2 12
D/PMS     (  909): releaseWL(44d3c3d0): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(4411bd98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/SyncManager(  909): failed sync operation  u0 (com.google), com.google.android.videos.sync, PERIODIC, latestRunTime 893857, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  909): not retrying sync operation because the error is a hard error:  u0 (com.google), com.google.android.videos.sync, PERIODIC, latestRunTime 896473, reason: Periodic
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=50 [2][1][0]
D/PMS     (  909): acquireWL(437b0fc8): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
D/PMS     (  909): releaseWL(44256bd0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.videos.sync/com.google/***** 0x1 WorkSource{10165}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1444/10028)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 296
D/libc    (  363): [NET]res_nsend:resplen=48
D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4896): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(437b0fc8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(4307aaa8): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/PMS     (  909): releaseWL(4307aaa8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/Process (  909): killProcessQuiet, pid=4653
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/Process (  909): killProcessQuiet, pid=4607
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  909): Killing 4653:com.htc.aurora/u0a47 (adj 15): empty #17
,I/ActivityManager(  909): Killing 4607:com.htc.htcpowermanager:remote/1000 (adj 15): empty #18
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/PMS     (  909): acquireWL(42ecc350): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.magazines/com.google/***** 0x1 909 1000 WorkSource{10151}
I/ActivityManager(  909): Recipient 4653
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  909): acquireWL(42ebd2a8): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(4411bd98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(42ea81c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(42ebd2a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=66 [3][2][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/ExternalAccountType( 1335): Unsupported attribute readOnly
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(42ea81c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4311f5a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,I/SyncAdapterService( 4497): Ignoring sync request for non-current account
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
,D/PMS     (  909): releaseWL(4311f5a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(43f78838): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/PMS     (  909): releaseWL(42ecc350): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.magazines/com.google/***** 0x1 WorkSource{10151}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4497/10151)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv er,ror 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  909): acquireWL(43facfa8): PARTIAL_WAKE_LOCK  *sync*/com.htc.cloudstorage.drive.db/com.google/***** 0x1 909 1000 WorkSource{10068}
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  909): Recipient 4607
I/ActivityManager(  909): Start proc com.htc.cloudstorage.drive for service com.htc.cloudstorage.drive/.SyncService: pid=4947 uid=10068 gids={50068, 3003, 5012, 1028, 1015}
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  909): Client connection lost with reason: 4
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,D/PMS     (  909): releaseWL(43f78838): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/CloudStorageManager( 4947): [getInstance] googledrive version: 6
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(43a91b80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(43a91b80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/MyGoogleDrive( 4947): [4961][GoogleDriveThreadedSyncAdapter] [onPerformSync]*Sync ABORT* Account not found(never cached)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(44017c90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=25 [4][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  909): releaseWL(43facfa8): PARTIAL_WAKE_LOCK  *sync*/com.htc.cloudstorage.drive.db/com.google/***** 0x1 WorkSource{10068}
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): acquireWL(442bd5f0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.music.MusicContent/com.google/***** 0x1 909 1000 WorkSource{10154}
,D/PMS     (  909): releaseWL(44017c90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,W/GA-SERVICE( 1230): Thread[Thread-122,5,main]:  Using destination https://ssl.google-analytics.com
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(430b2398): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(430b2398): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/GA-SERVICE( 1230): Thread[Thread-122,5,main]:  Using destination https://ssl.google-analytics.com
W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/com.google.android.apps.cloudprint.net.SessionProvider( 4896): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
,I/RemoteViews( 1123): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{428cc130 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.google.android.gms 1 6 3 12
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,I/ConfigStore( 3858): Config Database version: 1
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4896): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
D/libc    ( 4896): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4896): [NET] getaddrinfo-,err=8
D/libc    ( 4896): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4896): [NET] getaddrinfo-, 1
,D/libc    ( 4896): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
I/RemoteViews( 1123): com.google.android.gms (false,0)
D/libc    (  363): [NET] +++++ res_nsend xid =a05f +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4896): [NET] getaddrinfo_proxy-, success
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{428cc7c0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.google.android.gms 2 9 3 12
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com sj
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1123): com.google.android.gms (false,0)
,W/GLSActivity( 1372): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1372): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1372): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1372): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1372): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{428dfb68 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.google.android.gms 1 11 3 12
,W/MusicSyncAdapter( 3858): Sync failed due to an authentication issue.
,W/ContextImpl( 3858): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(430a57d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(442bd5f0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.music.MusicContent/com.google/***** 0x1 WorkSource{10154}
D/SyncManager(  909): failed sync operation  u0 (com.google), com.google.android.music.MusicContent, PERIODIC, latestRunTime 893875, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager(  909): not retrying sync operation because the error is a hard error:  u0 (com.google), com.google.android.music.MusicContent, PERIODIC, latestRunTime 897062, reason: Periodic
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [5][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1444/10028)
,D/PMS     (  909): acquireWL(4405f510): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3858 10154 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 3858): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/ContextImpl( 3858): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,W/ContextImpl( 3858): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 3858): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,D/PMS     (  909): acquireWL(43799cc0): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 909 1000 WorkSource{10096}
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3858): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  909): releaseWL(430a57d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,D/PMS     (  909): acquireWL(449c48a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/ExternalAccountType( 1335): Unsupported attribute readOnly
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 3858): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
I/MusicLeanback( 3858): Conditions not met for autocaching.
I/MusicLeanback( 3858): Stop autocaching.
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3858, uid=10154, userID:0
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/PMS     (  909): releaseWL(449c48a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  909): releaseWL(4405f510): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(4484a600): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,W/ContextImpl( 3858): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/DelayedSyncController( 4471): Delaying sync.
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  909): releaseWL(4484a600): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(44ac2c98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 3858): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  909): releaseWL(43799cc0): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
W/ContextImpl( 3858): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): acquireWL(430797d0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.docs/com.google/***** 0x1 909 1000 WorkSource{10100}
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/ContextImpl( 3858): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3858): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/ArtDownloadService( 3858): Setting cache size 0
W/ArtDownloadService( 3858): Setting cache size 0
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3858): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3858): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/cache
I/ActivityManager(  909): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=4977 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/PMS     (  909): releaseWL(44ac2c98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4896): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
,I/RemoteViews( 1123): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{429252c8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.google.android.gms 2 7 3 12
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1123): com.google.android.gms (false,0)
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4896): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{4299d0e0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.google.android.gms 0 7 2 12
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1123): com.google.android.gms (false,0)
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4896): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
D/libc    ( 4896): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4896): [NET] getaddrinfo-,err=8
D/libc    ( 4896): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4896): [NET] getaddrinfo-, 1
,D/libc    ( 4896): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =dc51 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4896): [NET] getaddrinfo_proxy-, success
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{4299de00 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.google.android.gms 0 9 2 12
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4977/10100)
,D/PMS     (  909): acquireWL(44ab7da0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4977/10100)
W/GAV2    ( 4977): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/PMS     (  909): releaseWL(44ab7da0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  909): acquireWL(445409f8): PARTIAL_WAKE_LOCK  SyncManager 0x1 4977 10100 null
,D/WifiService(  909): acquireWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@42ebfc68}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  909): acquireWL(443484d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=20 [10][2][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): releaseWL(443484d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
,D/libc    ( 4977): [NET] getaddrinfo+,hn 15(0x73736c2e677374),sn(),family 0,flags 4
D/libc    ( 4977): [NET] getaddrinfo-,err=8
D/libc    ( 4977): [NET] getaddrinfo+,hn 15(0x73736c2e677374),sn(),family 0,flags 1024
D/libc    ( 4977): [NET] getaddrinfo-, 1
,D/libc    ( 4977): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x73736c2e677374),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =fb4a +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 229
D/libc    (  363): [NET]res_nsend:resplen=49
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4977): [NET] getaddrinfo_proxy-, success
,I/global  ( 4977): call createSocket() return a new socket.
D/libc    ( 4977): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4977): [NET] getaddrinfo-, SUCCESS
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1123): com.google.android.gms (false,0)
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4896): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{42515378 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.google.android.gms 4 10 3 12
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4896): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1123): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{426cdff8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.google.android.gms 1 10 3 12
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/cloudprint
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/com.google.android.apps.cloudprint.net.SessionProvider( 4896): Exception during attempt to get authentication token. Message: User intervention required. Notification has been pushed.
,I/RemoteViews( 1123): com.google.android.gms (false,0)
D/libc    ( 4896): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4896): [NET] getaddrinfo-,err=8
D/libc    ( 4896): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4896): [NET] getaddrinfo-, 1
D/libc    ( 4896): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 14(0x7777772e676f6f),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =9f57 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4896): [NET] getaddrinfo_proxy-, success
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{428e5f18 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.google.android.gms 2 9 4 12
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com writely
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(42ecf4e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(44ab9590): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.cloudprint.cloudprintprovider/com.google/***** 0x1 WorkSource{10097}
,I/ActivityManager(  909): Killing 4079:com.android.vending/u0a73 (adj 15): empty #17
D/Process (  909): killProcessQuiet, pid=4079
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=24 [29][7][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  909): Recipient 4079
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
W/GLSActivity( 1372): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1372): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1372): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1372): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1372): 	at dalvik.system.NativeStart.run(Native Method)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/HttpIssuerBase( 4977): Attempt to consume entity of HttpIssuer when no request is executing.
,I/RemoteViews( 1123): com.google.android.gms (false,0)
,D/PMS     (  909): acquireWL(42b80bb8): PARTIAL_WAKE_LOCK  *sync*/com.htc.task.dm/com.google/***** 0x1 909 1000 WorkSource{10067}
E/HttpIssuerBase( 4977): Attempt to close HttpIssuer when no request is executing.
E/HttpIssuerBase( 4977): java.io.IOException
E/HttpIssuerBase( 4977): 	at Er.b(HttpIssuerBase.java:188)
E/HttpIssuerBase( 4977): 	at DV.b(DefaultAuthenticatedHttpIssuer.java:148)
E/HttpIssuerBase( 4977): 	at Pq.a(AccountMetadataUpdater.java:226)
E/HttpIssuerBase( 4977): 	at Pq.a(AccountMetadataUpdater.java:139)
E/HttpIssuerBase( 4977): 	at Qv.a(LegacySyncManager.java:776)
E/HttpIssuerBase( 4977): 	at Qv.a(LegacySyncManager.java:541)
E/HttpIssuerBase( 4977): 	at Qv.a(LegacySyncManager.java:95)
E/HttpIssuerBase( 4977): 	at Qx.run(LegacySyncManager.java:396)
E/HttpIssuerBase( 4977): 	at Vz.a(NetworkUtilitiesImpl.java:30)
E/HttpIssuerBase( 4977): 	at Qw.run(LegacySyncManager.java:393)
E/SyncManager( 4977): AuthenticatorException
E/SyncManager( 4977): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/SyncManager( 4977): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/SyncManager( 4977): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/SyncManager( 4977): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/SyncManager( 4977): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/SyncManager( 4977): 	at android.os.Binder.execTransact(Binder.java:412)
E/SyncManager( 4977): 	at dalvik.system.NativeStart.run(Native Method)
,W/GAV2    ( 4977): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/WifiService(  909): releaseWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@42ebfc68}
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{428d4ff0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/PMS     (  909): releaseWL(445409f8): PARTIAL_WAKE_LOCK  SyncManager 0x1 null
I/ActivityManager(  909): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5011 uid=10067 gids={50067, 3003, 5012}
D/PMS     (  909): releaseWL(42ecf4e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42fc7e60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,I/RemoteViews.Performance( 1123): com.google.android.gms 1 14 8 12
,D/Process (  909): killProcessQuiet, pid=4140
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
D/PMS     (  909): releaseWL(430797d0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.docs/com.google/***** 0x1 WorkSource{10100}
,I/ActivityManager(  909): Killing 4140:com.android.settings/1000 (adj 15): empty #17
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/PMS     (  909): acquireWL(43a48e00): PARTIAL_WAKE_LOCK  *sync*/com.google.android.location.reporting/com.google/***** 0x1 909 1000 WorkSource{10028}
D/PMS     (  909): releaseWL(42fc7e60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42f4ebb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(42f4ebb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(43920a90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(43920a90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  909): Start proc com.htc.task for content provider com.htc.task/.APICProviderDecorator: pid=5026 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,I/ActivityManager(  909): Recipient 4140
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  909): Client connection lost with reason: 4
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/userlocation.reporting
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/Process (  909): killProcessQuiet, pid=4426
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(42f46a30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,I/ActivityManager(  909): Killing 4426:com.facebook.katana/u0a26 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/PMS     (  909): releaseWL(42b80bb8): PARTIAL_WAKE_LOCK  *sync*/com.htc.task.dm/com.google/***** 0x1 WorkSource{10067}
,D/PMS     (  909): releaseWL(42f46a30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/TodoTaskshortcut( 5026): update TASK shortcut>
,D/Process (  909): killProcessQuiet, pid=4455
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4455:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 4455
,I/ActivityManager(  909): Recipient 4426
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  909): Client connection lost with reason: 4
,I/GCoreUlr( 1444): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService }, extras=null
,D/PMS     (  909): acquireWL(43a99d68): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 1444 10028 null
I/AdsMeasurementBroadcastReceiver( 1230): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1230): Unauthorized to start the main service
E/GCoreUlr( 1444): 
E/GCoreUlr( 1444): arx: BadAuthentication
E/GCoreUlr( 1444): 	at arj.a(SourceFile:411)
E/GCoreUlr( 1444): 	at byt.b(SourceFile:91)
E/GCoreUlr( 1444): 	at bxr.b(SourceFile:334)
E/GCoreUlr( 1444): 	at byd.b(SourceFile:355)
E/GCoreUlr( 1444): 	at byd.a(SourceFile:325)
E/GCoreUlr( 1444): 	at byd.a(SourceFile:304)
E/GCoreUlr( 1444): 	at lwj.a(SourceFile:128)
E/GCoreUlr( 1444): 	at lye.b(SourceFile:190)
E/GCoreUlr( 1444): 	at lye.a(SourceFile:137)
E/GCoreUlr( 1444): 	at lyi.onPerformSync(SourceFile:156)
E/GCoreUlr( 1444): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(43b27b98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/SyncManager(  909): failed sync operation  u0 (com.google), com.google.android.location.reporting, PERIODIC, latestRunTime 893893, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  909): not retrying sync operation because the error is a hard error:  u0 (com.google), com.google.android.location.reporting, PERIODIC, latestRunTime 898624, reason: Periodic
D/PMS     (  909): releaseWL(43a48e00): PARTIAL_WAKE_LOCK  *sync*/com.google.android.location.reporting/com.google/***** 0x1 WorkSource{10028}
D/PMS     (  909): releaseWL(43b27b98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1444/10028)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(43f95d38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  909): releaseWL(43f95d38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
,I/GCoreUlr( 1444): Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotSelected'}]}
,D/GCoreFlp( 1444): Unknown pending intent to remove.
,I/GCoreUlr( 1444): Unbound from all location providers
D/PMS     (  909): acquireWL(4356c1c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1444 10028 null
D/PMS     (  909): releaseWL(4356c1c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  909): releaseWL(43a99d68): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 null
,D/Process (  909): killProcessQuiet, pid=4690
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4690:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4690
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV2    ( 4796): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 4977): Thread[GAThread,5,main]: No campaign data found.
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
,D/ConnectivityService(  909): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver packageName:com.htc.cs.dm
,I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver packageName:com.google.android.videos
,I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver replacing:false
,W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
,D/PackageBroadcastService( 1230): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.cs.dm
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,W/SystemReader( 1262): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,I/PeopleContactsSync( 1230): CP2 sync disabled
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1230, uid=10028, userID:0
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1405): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.cs.dm
,I/[PluginManager]RegisterService( 1405): handle notify Blinkfeed plugin client changed
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
D/PMS     (  909): acquireWL(43f69328): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,I/ActivityManager(  909): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5059 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,W/SystemReader( 1262): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
,D/PhoneApp( 1249): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/PMS     (  909): releaseWL(43f69328): PARTIAL_WAKE_LOCK  Icing 0x1 null,
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
I/PackageManager(  909):   Scheme: "smsto"
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
I/PackageManager(  909):   Scheme: "mmsto"
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5059, uid=10073, userID:0
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
I/PackageManager(  909):   Scheme: "smsto"
,D/Finsky  ( 5059): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,D/ConnectivityService(  909): getAllNetworkInfo called by com.android.vending (5059/10073)
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
,D/PhoneApp( 1249): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
D/ConnectivityService(  909): getAllNetworkInfo called by com.android.vending (5059/10073)
,D/Finsky  ( 5059): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5059): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5059): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5059, uid=10073, userID:0
,D/Finsky  ( 5059): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5059): [1] 2.run: Finished loading 1 libraries.
,I/ActivityManager(  909): Killing 4117:com.google.android.apps.plus/u0a160 (adj 15): empty #17
D/Process (  909): killProcessQuiet, pid=4117
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/IcingCorporaProvider( 2897): Updating corpora: APPS=com.htc.cs.dm, CONTACTS=MAYBE
,D/Finsky  ( 5059): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5059): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 4117
,I/ActivityManager(  909): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=5094 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/IcingCorporaProvider( 2897): UpdateCorporaTask done [took 225 ms] updated apps [took 225 ms] 
,D/HtcFingerPrintQuickLaunchProvider( 5094): -onCreate()
,V/Settings:HtcSettingsApplication( 5094): [5094/5094] onCreate()
,D/Process (  909): killProcessQuiet, pid=4796
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 4796:com.google.android.gm/u0a107 (adj 15): empty #17
,D/PackageBroadcastService( 1230): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,I/PeopleContactsSync( 1230): CP2 sync disabled
I/[PluginManager]RegisterService( 1405): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.videos
,I/[PluginManager]RegisterService( 1405): handle notify Blinkfeed plugin client changed
,W/PackageManager(  909): Unable to load service info ResolveInfo{430d3570 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1230, uid=10028, userID:0
D/PMS     (  909): acquireWL(438c6a90): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
I/ActivityManager(  909): Resuming delayed broadcast
,I/IcingCorporaProvider( 2897): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,D/PMS     (  909): releaseWL(438c6a90): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 4796
,I/ActivityManager(  909): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5115 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@425a0e10 +
,I/Prism.WidgetManager( 1276): onLoadItems() +
,D/Settings:HtcWirelessFeatureFlags( 5094): id/is att sku: 99/false
,W/SystemReader( 5094): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 5094): Cannot find support_harman, use default value instead
,W/SystemReader( 5094): Cannot find effect_manager_id, use default value instead
,I/IcingCorporaProvider( 2897): UpdateCorporaTask done [took 98 ms] updated apps [took 98 ms] 
,E/Settings:HtcWrapHeaderInfo( 5094): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5094): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 5094): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5094): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5094): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5094): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5094): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5094): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5094): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5094): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5094): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5094): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5094): [supportHomeButton]support         :false
,W/FingerprintManager( 5094): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
D/PMS     (  909): acquireWL(44ac1060): PARTIAL_WAKE_LOCK  AsyncService 0x1 5115 10160 null
D/PMS     (  909): releaseWL(44ac1060): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/Process (  909): killProcessQuiet, pid=4784
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4784:com.htc.showme/u0a82 (adj 15): empty #17
D/PMS     (  909): acquireWL(44a86470): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 5115 10160 null
,E/Settings:HtcVoWifiWidgetEnabler( 5094): isSupportVoWifi: null
I/ActivityManager(  909): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 5094): Failed to find provider info for com.htc.vowifi
I/ActivityManager(  909): Recipient 4784
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(44a77058): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 5115 10160 null
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=18 [16][3][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(44a86470): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (5115/10160)
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (5115/10160)
,D/PMS     (  909): releaseWL(44a77058): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5094): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 5094): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5094): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5094): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5094): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5094): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5094): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5094): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5094): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5094): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5094): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5094): [supportHomeButton]support         :false
,W/FingerprintManager( 5094): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 5094): isSupportVoWifi: null
I/ActivityManager(  909): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 5094): Failed to find provider info for com.htc.vowifi
,E/Prism.WidgetManager( 1276): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1276): onLoadItems() -
,I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@425a0e10 -
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1276): AllAppsMgr addApps, already exist: ApplicationInfo(id=19, title=Play Movies & TV, componentNameComponentInfo{com.google.android.videos/com.google.android.youtube.videos.EntryPoint} appsContainer=<ALLAPPS>)
,D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  909): start
,I/Launcher( 1276): Deferring update until onResume
,D/Launcher( 1276): waitUntilResume // bindAppsUpdated
,D/PMS     (  909): acquireWL(428b8d80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10073}
,V/AlarmManager(  909): sending alarm PendingIntent{43f981c8: PendingIntentRecord{42fa8180 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450446102678, Int=0
,W/PackageManager(  909): Unable to load service info ResolveInfo{42942938 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  909): start
,D/PMS     (  909): releaseWL(428b8d80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 5059): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5059): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 5059): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5059): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5059): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/PhoneApp( 1249): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1249): -- N1 =0
,D/PhoneApp( 1249): -- N2 =0
,D/PhoneApp( 1249): -- N3 =0
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@425a0e10 +
,I/Prism.WidgetManager( 1276): onLoadItems() +
,E/Prism.WidgetManager( 1276): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1276): onLoadItems() -
,I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@425a0e10 -
,D/PMS     (  909): acquireWL(44549de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(44549de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(438a48f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10073}
,V/AlarmManager(  909): sending alarm PendingIntent{449ac858: PendingIntentRecord{44974200 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450446118016, Int=0
,D/PMS     (  909): releaseWL(438a48f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/PMS     (  909): acquireWL(44017300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{427d8800: PendingIntentRecord{42eac710 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=924004, Int=0
,D/PMS     (  909): acquireWL(449c5ef8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 909 1000 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): releaseWL(44017300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(437c4680): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(449c5ef8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/AutoSetting( 1405): service - has update message, not stop
,D/AutoSetting( 1405): service - mHandler: update timezone
D/PMS     (  909): releaseWL(437c4680): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 1531): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1531): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1531): service - onCreate()
,D/AutoSetting( 1531): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1531): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1593): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1531): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1531): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1531): service - mHandler: update timezone
,D/AutoSetting( 1531): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1531): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1531): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1531): service - showManualTimeZoneSelector() send notification (single)
,I/PhoneStatusBar( 1123): removeNotification.gc:60
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/Finsky  ( 5059): [1] 5.onFinished: Installation state replication succeeded.
,I/RemoteViews( 1123): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{428f1d48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.htc.htclocationservice 3 10 3 11
,D/PMS     (  909): acquireWL(445471f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=925428, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(445471f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43000dc8): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
,D/PMS     (  909): releaseWL(43000dc8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(4385dae0): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
,D/PMS     (  909): releaseWL(4385dae0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(44a29328): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
,D/PMS     (  909): releaseWL(44a29328): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  909): acquireWL(445ea640): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
,D/PMS     (  909): releaseWL(445ea640): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{43fb5438 u0 com.htc.htclocationservice/.AutoSettingService}
,D/AutoSetting( 1405): service - handleMessage() stop self
D/PMS     (  909): acquireWL(44a892d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(44a892d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/AutoSetting( 1531): service - handleMessage() stop self
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,D/AutoSetting( 1405): service - handleMessage() quit looper
,D/AutoSetting( 1405): service - onDestroy() END
,D/AutoSetting( 1531): service - onDestroy() END
,D/AutoSetting( 1531): service - handleMessage() quit looper
,D/Process (  909): killProcessQuiet, pid=4847
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4847:com.google.android.syncadapters.calendar/u0a108 (adj 15): empty #17
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
I/ActivityManager(  909): Recipient 4847
,D/PMS     (  909): acquireWL(43b1bf68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{427d8800: PendingIntentRecord{42eac710 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=957573, Int=0
,D/PMS     (  909): acquireWL(449c7cc8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 909 1000 null
D/PMS     (  909): releaseWL(43b1bf68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): acquireWL(44198228): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1168): environment dirty rate=20 [5][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1168): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1168): nl80211: survey data missing!
E/wpa_supplicant( 1168): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1168): environment dirty rate=0 [0][0][0]
D/PMS     (  909): acquireWL(42b70450): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.docs/com.google/***** 0x1 909 1000 WorkSource{10100}
,D/PMS     (  909): releaseWL(449c7cc8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  909): releaseWL(44198228): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(44545998): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(44545998): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(44a9ebc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(42b70450): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.docs/com.google/***** 0x1 WorkSource{10100}
,D/PMS     (  909): releaseWL(44a9ebc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  909): acquireWL(43a55fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): releaseWL(43a55fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(447c0df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=985429, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(447c0df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(444bc978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{427d8800: PendingIntentRecord{42eac710 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=987623, Int=0
,D/PMS     (  909): acquireWL(44f98e88): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 909 1000 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): releaseWL(444bc978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42ff87b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(44f98e88): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  909): releaseWL(42ff87b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  909): acquireWL(4307def0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42dd96b0: PendingIntentRecord{42d5ed58 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450446135727, Int=900000
,I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5156 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,V/AlarmManager(  909): sending alarm PendingIntent{438a03b0: PendingIntentRecord{449e16f8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450446206813, Int=0
,W/ContextImpl( 5156): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 5156): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 5156): MY_DEBUG = false
,D/PMS     (  909): acquireWL(4472df98): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5156 1000 null
,D/SmartSyncUtils( 5156): isEpsOn(), nState = 0
,D/PMS     (  909): releaseWL(4307def0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/PMS     (  909): releaseWL(4472df98): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  909): acquireWL(444a0f30): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5156 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 5156): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 5156): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 2, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 5156): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 5156): SettingOnTime = 1450486800000, randomSettingOnTime = 1450484844000
,D/SmartSyncScreenOnOffTimeReceiver( 5156): SettingOffTime = 1450483200000, randomSettingOffTime = 1450484054000
,D/SmartSyncScreenOnOffTimeReceiver( 5156): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 5156): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 5156): bNightModeTurnOffOnce = false
,D/PMS     (  909): releaseWL(444a0f30): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/Process (  909): killProcessQuiet, pid=4878
,I/ActivityManager(  909): Killing 4878:com.google.android.videos/u0a165 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  909): Recipient 4878
D/MediaRouterService(  909): Client com.google.android.videos (pid 4878): Died!
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(44ac1128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1123): closing low battery warning: level=100
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(44ac1128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1230/10028)
,W/GA-SERVICE( 1230): Thread[Thread-122,5,main]: hit:_gmsv=1-5089038&ul=en-gb&sr=720x1184&ht=1450446091156&a=1731142367&sc=start&AppUID=10151&aid=com.google.android.apps.magazines&cid=555235a2-953e-473b-8151-55e062e9c995&av=3.2.1&cd16=Ignoring+sync+request+for+non-current+account&v=1&t=appview&an=Google+Play+Newsstand&cd11=false&tid=UA-32428711-6&_u=.nOQKSTB&_v=ma1b6&cd=Debug&qt=120388&z=87
,W/GA-SERVICE( 1230): Thread[Thread-122,5,main]: hit:_gmsv=1-5089038&ev=0&ul=en-gb&sr=720x1184&ht=1450446091157&a=1195592525&AppUID=10151&aid=com.google.android.apps.magazines&ea=Sync+Skipped&cid=555235a2-953e-473b-8151-55e062e9c995&av=3.2.1&ec=Debug&v=1&t=event&el=&an=Google+Play+Newsstand&tid=UA-32428711-6&_u=.C&_v=ma1b6&cd=Debug&qt=120387&z=88
,D/libc    ( 1230): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 4
D/libc    ( 1230): [NET] getaddrinfo-,err=8
D/libc    ( 1230): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 1024
D/libc    ( 1230): [NET] getaddrinfo-, 1
D/libc    ( 1230): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =a818 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 110
D/libc    (  363): [NET]res_nsend:resplen=102
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1230): [NET] getaddrinfo_proxy-, success
I/global  ( 1230): call createSocket() return a new socket.
D/libc    ( 1230): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 1230): [NET] getaddrinfo-, SUCCESS
,D/PMS     (  909): acquireWL(44658e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/PMS     (  909): releaseWL(44658e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(444a5b08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1045429, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(444a5b08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(44453608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(44453608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(44445308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): releaseWL(44445308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(440c31b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1105429, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(440c31b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(440b5938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(440b5938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43faf468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1165429, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43faf468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1372): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1372): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1372): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1372): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1372): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1593): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1123): com.google.android.gms (false,0)
,E/PlayEventLogger( 5059): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5059): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5059): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 5059): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5059): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 5059): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5059): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 5059): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1123): release indeterminate drawable android.widget.OnDemandProgressBar{425247b8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1123): com.google.android.gms 1 9 3 12
,D/libc    ( 5059): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 5059): [NET] getaddrinfo-,err=8
D/libc    ( 5059): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 5059): [NET] getaddrinfo-, 1
,D/libc    ( 5059): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =7cbf +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 184
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 5059): [NET] getaddrinfo_proxy-, success
,I/global  ( 5059): call createSocket() return a new socket.
D/libc    ( 5059): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 5059): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 5059): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 5059): [NET] getaddrinfo-,err=8
,D/PMS     (  909): acquireWL(43c11c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/PMS     (  909): releaseWL(43c11c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  909): acquireWL(4386f370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1225429, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4386f370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4385b0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(4385b0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(436054e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(436054e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(4307a840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1285429, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4307a840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42e116b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(42e116b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42aa1eb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(42aa1eb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=100
,D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4306e690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1345428, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4306e690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42bf1070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(42bf1070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42a1d648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(42a1d648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42fc2b68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1405429, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42fc2b68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42ece660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42ece660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43033b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43033b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42f33bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10073}
,V/AlarmManager(  909): sending alarm PendingIntent{42d88ae0: PendingIntentRecord{42fa8180 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450446656204, Int=0
,D/PMS     (  909): releaseWL(42f33bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 5059): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5059): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 5059): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5059): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5059): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/PMS     (  909): acquireWL(43019178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1465429, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43019178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42df2c78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10073}
,V/AlarmManager(  909): sending alarm PendingIntent{42e9a660: PendingIntentRecord{44974200 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450446671380, Int=0
,D/PMS     (  909): releaseWL(42df2c78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 5059): [1] 5.onFinished: Installation state replication succeeded.
,D/Process (  909): killProcessQuiet, pid=4497
,I/ActivityManager(  909): Killing 4497:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  909): Recipient 4497
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(43092cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(43092cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(44aab540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1525428, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(44aab540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42ee8a00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42ee8a00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1123): closing low battery warning: level=100
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42f470d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42f470d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43180d58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1585429, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43180d58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(445123a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(445123a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42d88aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1645429, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42d88aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(430947d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(430947d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42f269b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1705428, Int=0
,D/PMS     (  909): releaseWL(42f269b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(438b3400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(438b3400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1123): closing low battery warning: level=100
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42d88138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42d88138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43b3b970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1765428, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43b3b970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(44a7d0a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(44a7d0a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  909): updateBatteryInfo
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/PMS     (  909): acquireWL(430138a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(430138a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  909): acquireWL(44a819a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1825429, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  909): Prepared write state in 29ms
,I/ProcessStatsService(  909): Prepared write state in 19ms
,I/ProcessStatsService(  909): Prepared write state in 9ms
,D/PMS     (  909): releaseWL(44a819a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  909): Pruning old procstats: /data/system/procstats/state-2015-12-17-18-44-00.bin
,D/PMS     (  909): acquireWL(4307d2c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
I/BatteryService(  909): n_update end
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(4307d2c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
,I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(449c3c58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42d65958: PendingIntentRecord{42d9ed68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1885429, Int=0
,I/IntentController( 1123): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(449c3c58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 5202): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5202): ====startRecUseTime====
D/htc.customization.log.level( 5202):  is 
W/CustomizationLogLevel( 5202): Level value is invalid, use default level 2
D/CustomizationManager( 5202):  Read ACC file spent 0.111 (s)
D/CIDMapFileReader( 5202): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5202): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5202): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5202): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5202): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5202): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5202): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5202): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5202): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5202): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5202): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5202): Parsing tag category name = system
I/CustomizationCIDLoader( 5202): Parsing tag category name = application
I/CustomizationCIDLoader( 5202): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5202): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5202): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5202): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5202): Parsing tag category name = Settings
D/CustomizationManager( 5202):  Read CID file spent 0.164 (s)
D/CustomizationManager( 5202):  All configurations done spent 0.164 (s)
W/HtcNativeFlag( 5202): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5202): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5202): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5202): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  909): deletePackageAsUser: pkg=com.test.thalitest, pid=5202, uid=2000 user=0
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
W/asset   (  909): Copying FileAsset 0x62ac72f0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  909): Skipping PackageSetting{42cc5798 com.example.hello/10356} due to missing metadata
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
D/DotMatrix( 1593): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1593): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1593): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1123): ApplicationsIntentReceiver replacing:false
I/acms    ( 1925): Unregistering com.test.thalitest
E/acms    ( 1925): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1444): Ignoring removeGeofence because network location is disabled.
D/PMS     (  909): acquireWL(4306b6b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1444 10028 null
D/PMS     (  909): releaseWL(4306b6b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/VoicemailCleanupService( 1302): Cleaning up data for package: com.test.thalitest
W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
I/Launcher( 1276): Deferring update until onResume
D/Launcher( 1276): waitUntilResume // bindAppsRemoved
D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
D/PackageBroadcastService( 1230): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
I/ActivityManager(  909): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=5216 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/InputMethodManagerService(  909): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
W/SystemReader( 1262): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
E/ExternalAccountType( 1335): Unsupported attribute readOnly
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
I/MultiDex( 5216): install
I/MultiDex( 5216): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/MultiDex( 5216): loading existing secondary dex files
I/MultiDex( 5216): load found 1 secondary dex files
I/MultiDex( 5216): install done
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1249 :
D/PhoneApp( 1249): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  909): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=5232 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PeopleContactsSync( 1230): CP2 sync disabled
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1230, uid=10028, userID:0
I/Icing   ( 1230): doRemovePackageData com.test.thalitest
D/PMS     (  909): acquireWL(449b25d8): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
I/ProviderInstaller( 5216): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  909): releaseWL(449b25d8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 5232): install
I/MultiDex( 5232): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  909): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 5232): loading existing secondary dex files
I/MultiDex( 5232): load found 1 secondary dex files
I/MultiDex( 5232): install done
I/ProviderInstaller( 5232): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  909): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1405): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1405): handle notify Blinkfeed plugin client changed
D/Process (  909): killProcessQuiet, pid=4947
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 4947:com.htc.cloudstorage.drive/u0a68 (adj 15): empty #17
D/Prism.PackageStateRece_( 1276): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2897): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  909): Recipient 4947
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5253 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/PMS     (  909): acquireWL(444e5ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(444e5ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
E/SQLiteDatabase( 5216): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 5216): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5216): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5216): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5216): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5216): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5216): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5216): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5216): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5216): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5216): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5216): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5216): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5216): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5216): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5216): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 5216): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 5216): 	at ctn.run(SourceFile:985)
W/dalvikvm( 5216): threadid=12: thread exiting with uncaught exception (group=0x420dde30)
E/AndroidRuntime( 5216): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5216): Process: com.google.android.gms.drive, PID: 5216
E/AndroidRuntime( 5216): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5216): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5216): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5216): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5216): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5216): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5216): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5216): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5216): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5216): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5216): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5216): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5216): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5216): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5216): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 5216): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 5216): 	at ctn.run(SourceFile:985)
D/PMS     (  909): acquireWL(444522b0): PARTIAL_WAKE_LOCK  Icing 0x1 1230 10028 null
W/ContextImpl( 5253): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/ActivityManager(  909): App crashed! Process: com.google.android.gms.drive
D/Process ( 5216): killProcess, pid=5216
D/Process ( 5216): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  909): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
E/SQLiteLog( 2897): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2897): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x636221e0
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
E/SQLiteDatabase( 5253): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5253): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5253): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5253): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5253): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5253): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5253): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5253): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5253): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5253): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5253): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5253): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5253): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5253): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5253): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5253): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5253): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5253): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5253): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5253): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5253): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5253): threadid=10: thread exiting with uncaught exception (group=0x420dde30)
E/AndroidRuntime( 5253): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5253): Process: com.android.keychain, PID: 5253
E/AndroidRuntime( 5253): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5253): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5253): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5253): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5253): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5253): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5253): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5253): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5253): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5253): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5253): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5253): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5253): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5253): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5253): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5253): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5253): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5253): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5253): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5253): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  909): Recipient 5216
I/ActivityManager(  909): Process com.google.android.gms.drive (pid 5216) has died.
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
E/IcingCorporaProvider( 2897): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2897): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2897): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2897): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2897): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2897): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2897): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2897): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2897): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2897): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2897): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2897): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2897): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2897): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2897): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2897): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2897): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2897): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2897): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2897): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2897): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2897): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2897): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2897): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2897): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2897): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2897): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2897): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2897): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2897): 	... 15 more
W/IcingCorporaProvider( 2897): notifyTableChanged failed.
W/IcingCorporaProvider( 2897): Table change notification failed for TableStorageSpec[applications]
I/IcingCorporaProvider( 2897): UpdateCorporaTask done [took 311 ms] updated apps [took 311 ms] 
E/ActivityManager(  909): App crashed! Process: com.android.keychain
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5271 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/PMS     (  909): releaseWL(444522b0): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/Process ( 5253): killProcess, pid=5253
D/Process ( 5253): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450447111583.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  909): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  909): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  909): 	... 4 more
I/ActivityManager(  909): Recipient 5253
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.android.keychain (pid 5253) has died.
D/AppTag  ( 5271): getInstance(Context context)
W/ActivityManager(  909): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 5271): getInstance(Context context)
D/AppTag  ( 5271): onCreate()
D/PMS     (  909): acquireWL(438a5f68): PARTIAL_WAKE_LOCK  AsyncService 0x1 5115 10160 null
I/ActivityManager(  909): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5289 uid=10098 gids={50098, 3003, 5012}
D/PMS     (  909): releaseWL(438a5f68): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/DeviceManagement( 5289): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5289 dbg=false s=true
I/DeviceManagement( 5289): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5289): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5289): WorkflowService: Starting workflow service
I/DeviceManagement( 5289): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@42542448] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5289): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5289): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5289): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5289): ModelRegistry: Loading model meta data from resources...
W/PackageManager(  909): Unable to load service info ResolveInfo{42e9cdd8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  909): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5304 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 5289): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 5289): SessionStateController: Checking invariants...
D/Documents( 5304): Loading roots for com.android.providers.downloads.documents
D/Documents( 5304): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 5304): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5304): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5304): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5304): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5304): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5304): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5304): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5304): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5304): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5304): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5304): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5304): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5304): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5304): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5304): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5304): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5304): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5304): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5304): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5304): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5304): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5304): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5304): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5304): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5304): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5304): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5304): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5304): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5304): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5304): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5304): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5304): threadid=1: thread exiting with uncaught exception (group=0x420dde30)
E/AndroidRuntime( 5304): FATAL EXCEPTION: main
E/AndroidRuntime( 5304): Process: com.android.documentsui, PID: 5304
E/AndroidRuntime( 5304): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5304): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5304): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5304): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5304): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5304): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5304): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5304): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5304): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5304): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5304): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5304): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5304): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5304): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5304): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5304): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5304): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5304): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5304): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5304): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5304): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5304): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5304): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5304): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5304): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5304): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5304): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5304): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5304): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5304): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5304): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5304): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5304): 	... 10 more
I/ActivityManager(  909): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5318 uid=10023 gids={50023, 1028, 1015, 1023}
D/Process (  909): killProcessQuiet, pid=3858
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 3858:com.google.android.music:main/u0a154 (adj 15): empty #17
E/ActivityManager(  909): App crashed! Process: com.android.documentsui
D/GCM     ( 1372): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
D/GCM     ( 1372): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@425a0e10 +
I/Prism.WidgetManager( 1276): onLoadItems() +
D/Process (  909): killProcessQuiet, pid=4471
I/ActivityManager(  909): Killing 4471:com.android.chrome/u0a96 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  909): Recipient 4471
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 3858
D/MediaRouterService(  909): Client com.google.android.music (pid 3858): Died!
D/ExternalStorage( 5318): After updating volumes, found 1 active roots
E/SQLiteDatabase( 5289): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5289): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5289): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5289): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 5289): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 5289): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 5289): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 5289): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 5289): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5289): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 5289): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5289): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 5289): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 5289): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 5289): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5289): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5289): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5289): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 5289): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 5289): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 5289): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
D/PMS     (  909): acquireWL(42fee5a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{42822218: PendingIntentRecord{42e4af88 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1599142, Int=0
E/SQLiteDatabase( 5289): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5289): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5289): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5289): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5289): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 5289): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 5289): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 5289): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 5289): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 5289): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 5289): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5289): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5289): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5289): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 5289): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@42542448]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 5289): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 5289): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 5289): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 5289): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 5289): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 5289): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 5289): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 5289): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 5289): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 5289): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 5289): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 5289): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 5289): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 5289): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 5289): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 5289): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 5289): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 5289): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 5289): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 5289): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 5289): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 5289): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 5289): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 5289): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 5289): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 5289): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 5289): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 5289): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 5289): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 5289): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 5289): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 5289): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 5289): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Documents( 5304): Loading roots for com.android.providers.media.documents
I/DeviceManagement( 5289): WorkflowService: Stopping workflow service
V/AlarmManager(  909): sending alarm PendingIntent{42eed820: PendingIntentRecord{42f17a60 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1794565, Int=0
V/AlarmManager(  909): sending alarm PendingIntent{4403ebc0: PendingIntentRecord{42f2d2f8 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1450446990451, Int=0
D/Process ( 5304): killProcess, pid=5304
D/Process ( 5304): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450447112135.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  909): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  909): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  909): 	... 4 more
I/ActivityManager(  909): Recipient 5304
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  909): killProcessQuiet, pid=4919
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4919:com.google.android.apps.cloudprint/u0a97 (adj 15): empty #17
I/ActivityManager(  909): Process com.android.documentsui (pid 5304) has died.
I/ActivityManager(  909): Recipient 4919
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  909): killProcessQuiet, pid=4896
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeDyingProviderLocked:13474 com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked:13550 
I/ActivityManager(  909): Killing 4896:com.google.android.apps.cloudprint:sync/u0a97 (adj 15): depends on provider com.google.android.apps.cloudprint/.printdialog.database.CloudPrintContentProvider in dying proc com.google.android.apps.cloudprint
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 4896
D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  909): start
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1123): closing low battery warning: level=100
D/PowerUI ( 1123): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1593): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1123): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/ConnectivityService(  909): Sampling interval elapsed, updating statistics ..
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): acquireWL(431125d8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1372 10028 null
D/PMS     (  909): releaseWL(431125d8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
D/ConnectivityService(  909): Done.
D/ConnectivityService(  909): Setting timer for 720seconds
D/PMS     (  909): acquireWL(42ef1b28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/PMS     (  909): releaseWL(42ef1b28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
W/Uploader( 1230): No account for auth token provided
W/AppWidgetServiceImpl(  909): updateAppWidget failed! callbacks null
I/mbh     ( 1230): I/O exception (javax.net.ssl.SSLException) caught when processing request: Write error: ssl=0x6b897e28: I/O error during system call, Broken pipe
I/mbh     ( 1230): Retrying request
D/libc    ( 1230): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1230): [NET] getaddrinfo-,err=8
D/libc    ( 1230): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1230): [NET] getaddrinfo-, 1
D/libc    ( 1230): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d531 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1230): [NET] getaddrinfo_proxy-, success
I/global  ( 1230): call createSocket() return a new socket.
D/libc    ( 1230): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
D/libc    ( 1230): [NET] getaddrinfo-, SUCCESS
I/BatteryController( 1123): status:5 level:100 unsupport:false plugged:true

```
