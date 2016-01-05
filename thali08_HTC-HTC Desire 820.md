#### Test 549702617d40def_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
--------- beginning of /dev/log/system
D/WIFI_ICON( 1120): WifiActivity: 0
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/cutils-trace( 4385): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4385): ====startRecUseTime====
D/htc.customization.log.level( 4385):  is 
W/CustomizationLogLevel( 4385): Level value is invalid, use default level 2
D/CustomizationManager( 4385):  Read ACC file spent 0.063 (s)
D/CIDMapFileReader( 4385): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4385): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4385): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4385): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4385): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4385): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4385): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4385): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4385): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4385): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4385): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4385): Parsing tag category name = system
I/CustomizationCIDLoader( 4385): Parsing tag category name = application
I/CustomizationCIDLoader( 4385): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4385): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4385): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4385): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4385): Parsing tag category name = Settings
D/CustomizationManager( 4385):  Read CID file spent 0.112 (s)
D/CustomizationManager( 4385):  All configurations done spent 0.112 (s)
W/HtcNativeFlag( 4385): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4385): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4385): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4385): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  910): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  910): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4385
D/PMS     (  910): acquireHCC(42145268): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 910 1000 null
D/PMS     (  910): acquireHCC(420c00e0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 910 1000 null
I/Intent  (  910): @test_code: getHtcIntentFlag: 0 obj: 1108808824
D/PMS     (  910): acquireWL(424c9e10): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 910 1000 null
I/FeedHostManager( 1274): [onPause]
I/FeedProviderManager( 1274): onPause
I/FeedHostManager( 1274): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41ce46f0
I/SocialFeedProvider( 1274): +onPause
I/SocialFeedProvider( 1274): -onPause
I/ActivityManager(  910): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4396 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1274): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4396): Binding Chromium to main looper Looper (main, tid 1) {41b2b290}
I/LibraryLoader( 4396): Expected native library version number "",actual native library version number ""
I/chromium( 4396): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4396): Initializing chromium process, renderers=0
D/PMS     (  910): acquireWL(42351a60): PARTIAL_WAKE_LOCK  AudioMix 0x1 365 1013 null
D/PMS     (  910): acquireWL(421be550): PARTIAL_WAKE_LOCK  AudioMix 0x1 365 1013 null
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4204c890:true
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  910): releaseWL(42351a60): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4396): 1102323592: getState(). Returning 12
I/Adreno-EGL( 4396): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4396): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4396): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4396): Local Branch: 
I/Adreno-EGL( 4396): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4396): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4396):                  aa63bbd948f41d15fc72f585e
W/chromium( 4396): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4396): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4396): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4396): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4396): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4396): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4396): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4396): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4396): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4396): CordovaWebView is running on device made by: HTC
,D/PMS     (  910): acquireWL(421091d0): PARTIAL_WAKE_LOCK  Icing 0x1 2238 10028 null
,W/AwContents( 4396): nativeOnDraw failed; clearing to background color.
,D/PMS     (  910): releaseWL(421091d0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  910): acquireWL(42370f68): PARTIAL_WAKE_LOCK  Icing 0x1 2238 10028 null
,I/ActivityManager(  910): Displayed com.test.thalitest/.MainActivity: +302ms
W/ResourceType( 4396): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4396): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b73638, mServedView=org.apache.cordova.engine.SystemWebView{41b392a0 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  910): Disable input method client, pid=1274
I/InputMethodManagerService(  910): Enable input method client, pid=4396
,W/AwContents( 4396): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1213): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1213): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/PMS     (  910): releaseWL(424c9e10): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/PMS     (  910): releaseWL(42370f68): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WIFI_ICON( 1120): WifiActivity: 1
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/JsMessageQueue( 4396): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4396): JniHelper::setJavaVM(0x41604048), pthread_self() = 1663304224
,D/JX-Cordova( 4396): jxcore cordova android initializing
,I/dalvikvm-heap( 4396): Grow heap (frag case) to 11.589MB for 63974-byte allocation
,I/dalvikvm-heap( 4396): Grow heap (frag case) to 11.644MB for 95956-byte allocation
,I/dalvikvm-heap( 4396): Grow heap (frag case) to 11.728MB for 143930-byte allocation
,I/ActivityManager(  910): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4444 uid=10077 gids={50077}
D/PMS     (  910): acquireWL(43f71cd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10077}
,V/AlarmManager(  910): sending alarm PendingIntent{4216e548: PendingIntentRecord{426a6570 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1451956865216, Int=60000
,D/PMS     (  910): releaseWL(43f71cd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,I/dalvikvm-heap( 4396): Grow heap (frag case) to 11.845MB for 215890-byte allocation
,D/SMSBackup( 4444): SMSBackupAgentService started
,D/SMSBackup( 4444): Checking restore status
D/SMSBackup( 4444): Restore complete
,D/SMSBackup( 4444): cancelCheckAlarm
,D/SMSBackup( 4444): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  910): killProcessQuiet, pid=3183
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3183:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/dalvikvm-heap( 4396): Grow heap (frag case) to 12.025MB for 323830-byte allocation
I/ActivityManager(  910): Recipient 3183
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4396): Grow heap (frag case) to 12.669MB for 728606-byte allocation
,I/dalvikvm-heap( 4396): Grow heap (frag case) to 13.274MB for 1092904-byte allocation
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1120): WifiActivity: 0
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,I/dalvikvm-heap( 4396): Grow heap (frag case) to 14.134MB for 1639352-byte allocation
,I/dalvikvm-heap( 4396): Grow heap (frag case) to 15.486MB for 2459024-byte allocation
,W/CpuWake (  910): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  910): <<release mCpuPerf_Freq wakelock
,D/PMS     (  910): releaseHCC(42145268): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  910): releaseHCC(420c00e0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4396): Grow heap (frag case) to 17.618MB for 3688532-byte allocation
,W/jxcore-log( 4396): Initializing JXcore engine
,W/jxcore-log( 4396): JXcore engine is ready
,W/jxcore-log( 4396): Starting JXcore engine
,W/jxcore-log( 4396): Platform android
W/jxcore-log( 4396): 
,W/jxcore-log( 4396): Process ARCH arm
W/jxcore-log( 4396): 
,I/SensorManager(  910): mEventCount = 1050
,D/PMS     (  910): acquireWL(425ed900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,D/WifiDataStallTracker(  910): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  910): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  910): updateDataStallInfo: mDataStallTxRxSum={txSum=79 rxSum=65} preTxRxSum={txSum=78 rxSum=64}
D/WifiDataStallTracker(  910): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  910): onDataStallAlarm: tag=20442 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=20443 delay=15s
V/AlarmManager(  910): sending alarm PendingIntent{421b6818: PendingIntentRecord{425e9478 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=106139, Int=0
D/PMS     (  910): releaseWL(425ed900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4396): JXcore Cordova bridge is ready!
I/jxcore-log( 4396): 
,W/jxcore-log( 4396): JXcore engine is started
,I/chromium( 4396): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4396): Toggling radios to true
I/jxcore-log( 4396): 
,D/BluetoothAdapter( 4396): enable(): BT is already enabled..!
D/PMS     (  910): releaseWL(421be550): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiManager( 4396): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
D/WifiService(  910): New client listening to asynchronous messages
,W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  910): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 2
W/Settings:Agent(  910): >> traceCallingStack()
W/Settings:Agent(  910): Process.myPid(): 910
W/Settings:Agent(  910): Process.myTid(): 1349
W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
W/Settings:Agent(  910): 
,W/System.err(  910): java.lang.Throwable: stack dump
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  910): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  910): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  910): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  910): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  910): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  910): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  910): 
,W/Settings:Agent(  910): << traceCallingStack(): 1(ms)
,D/WifiManager( 4396): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiManager( 4396): reconnect: Base Package Name=com.test.thalitest, uid=10348
,D/WifiNative-wlan0(  910): doBoolean: DISCONNECT
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): TDLS: Tear down peers
,I/wpa_supplicant( 1160): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4396): Radios toggled
I/jxcore-log( 4396): 
D/WifiService(  910): setWifiEnabled: true pid=4396, uid=10348
E/WifiService(  910): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  910): isSprintWifiRestricted(): false
I/WifiService(  910): isMdmWifiRestricted(): false
D/WifiSettingsStore(  910): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1160): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1160): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1160): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1160): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1160): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1160): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1160): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1160): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb870cbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
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
,D/wpa_supplicant( 1160): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
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
D/wpa_supplicant( 1160): EAPOL: External notification - portValid=0,
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1160): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1160): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1160): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1160): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1160): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1160): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1160): nl80211: Ignore disconnect event triggered during reassociation
,D/WifiNative-wlan0(  910):    returned true
D/WifiPerfLock(  910): release()
D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): Power_Mode_Type mode = 0
I/wpa_supplicant( 1160): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
D/Tethering(  910): [isWifi] getHotspotEnabled: false
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
,D/Tethering(  910): interfaceStatusChanged wlan0, false
,D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  910): acquireWL(425da820): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
D/WifiP2pService(  910): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/DhcpStateMachine(  910): [RunningState] Stop DHCP
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  910): doBoolean: RECONNECT
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): Fast associate: Old scan results
I/wpa_supplicant( 1160): wpa_supplicant_scan enter
I/wpa_supplicant( 1160): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1160): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1160): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1160): Scan req (ret=0) - timeout 30 secs
D/WifiNative-wlan0(  910):    returned true
D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiStateMachine(  910): Enter handleNetworkDisconnect
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20443 mDataStallAlarmIntent=PendingIntent{424ce3f8: PendingIntentRecord{425e9478 android broadcastIntent}}
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
,D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  910): Provision feature enable=false
,D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1823/10178)
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): Power_Mode_Type mode = 0
I/wpa_supplicant( 1160): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WISPrService( 4172): >>>>>WISPrService start isConnected = false<<<<<
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/WifiNative-wlan0(  910):    returned true
D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
,D/UsbnetStateTracker(  910): isAvailable+-
,D/WISPrService( 4172): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/WifiService(  910): New client listening to asynchronous messages
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
D/MDST    (  910): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/libc    (  358): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    (  358): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  358): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  910): Exit handleNetworkDisconnect
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/libc    (  358): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    (  358): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/libc    (  358): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    (  358): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  358): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/ConnectivityService(  910): resetConnections(wlan0, 3)
D/PMS     (  910): acquireWL(432db998): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10028 null
D/libc    (  358): [NET] entry_id:6   entry:0xb8920948  removed 
D/libc    (  358): [NET] entry_id:4   entry:0xb8920038  removed 
D/libc    (  358): [NET] entry_id:3   entry:0xb891fec0  removed 
D/libc    (  358): [NET] entry_id:2   entry:0xb8920108  removed 
D/libc    (  358): [NET] entry_id:7   entry:0xb8920270  removed 
D/libc    (  358): [NET] entry_id:5   entry:0xb8920840  removed 
D/libc    (  358): [NET] entry_id:1   entry:0xb8920438  removed 
D/libc    (  358): [NET] entry_id:8   entry:0xb8920328  removed 
,D/libc    (  358): *************************
D/libc    (  358): *** DNS CACHE FLUSHED ***
D/libc    (  358): *************************
,D/WISPrService( 4172): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4172): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1823/10178)
D/PMS     (  910): acquireWL(4259d168): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
,I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:0
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I//system/bin/ip(  358): RTNETLINK answers: No such process
,I/logwrapper(  358): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  910): acquireWL(43617c58): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
D/WifiNative-wlan0(  910): doBoolean: SCAN
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  910):    returned false
D/BatSI   (  910): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  910): releaseWL(4259d168): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1367/10028)
D/PMS     (  910): releaseWL(432db998): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
,I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
,D/PMS     (  910): releaseWL(43617c58): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  910): bSetPropertyMultiRAB:false
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  910): ipv4Default null
I/Tethering(  910): No IPv4 upstream interface, giving up.
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1883/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(42e2c458): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(42e2c458): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1429/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1823/10178)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4282/10100)
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
I/NetworkMonitor( 3847): type=WIFI subType= reason=null isConnected=false
,D/CaptivePortalTracker(  910): NoActiveNetworkState
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (3847/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10075)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4282/10100)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (2451/10021)
,I/ActivityManager(  910): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4467 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4467): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4467): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4467): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4467): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk,
,V/DexLibLoader( 4467): Preparing secondary program dexes.
V/DexLibLoader( 4467): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4467): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4467): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary,
V/DexLibLoader( 4467): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4467): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4467): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4467): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4467): Dex already copied
D/OdexVerifier( 4467): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4467): Creating class loader
,V/DexLibLoader( 4467): Finished creating class loader
V/DexLibLoader( 4467): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4467): Dex already copied
D/OdexVerifier( 4467): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4467): Creating class loader,
,V/DexLibLoader( 4467): Finished creating class loader
V/DexLibLoader( 4467): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4467): Dex already copied
D/OdexVerifier( 4467): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4467): Creating class loader,
V/DexLibLoader( 4467): Finished creating class loader
V/DexLibLoader( 4467): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4467): Dex already copied
,D/OdexVerifier( 4467): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4467): Creating class loader
,V/DexLibLoader( 4467): Finished creating class loader
,V/DexLibLoader( 4467): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4467): DexLibLoader.ensureDexLoaded took 21 ms
,W/dalvikvm( 4467): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1160): nl80211: Event message available
D/wpa_supplicant( 1160): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1160): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1160): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1160): nl80211: Survey data missing
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1160): Sorted scan results
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1160): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-46
I/wpa_supplicant( 1160): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-47
I/wpa_supplicant( 1160): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
I/wpa_supplicant( 1160): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1160): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1160): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1160): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
D/wpa_supplicant( 1160): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1160): Add randomness: count=8 entropy=0
D/wpa_supplicant( 1160): Add randomness: count=9 entropy=1
D/wpa_supplicant( 1160): Add randomness: count=10 entropy=2
D/wpa_supplicant( 1160): Add randomness: count=11 entropy=3
D/wpa_supplicant( 1160): Add randomness: count=12 entropy=4
D/wpa_supplicant( 1160): Add randomness: count=13 entropy=5
D/wpa_supplicant( 1160): Add randomness: count=14 entropy=6
D/wpa_supplicant( 1160): Add randomness: count=15 entropy=7
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
D/wpa_supplicant( 1160): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1160): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1160): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1160): wpa_supplicant_pick_network+
I/wpa_supplicant( 1160): Selecting BSS from priority group 1
I/wpa_supplicant( 1160): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1160): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1160): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1160): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1160):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1160):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-46
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
I/,wpa_supplicant( 1160): selected network = 1
D/wpa_supplicant( 1160): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb870e4e8  current_ssid=0x0
D/wpa_supplicant( 1160): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1160): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1160): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1160): check if in concurrent case
I/wpa_supplicant( 1160): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1160): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1160): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1160): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1160): RSN: PMKSA cache search - network_ctx=0xb870e4e8 try_opportunistic=0
D/wpa_supplicant( 1160): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1160): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1160): State: SCANNING -> ASSOCIATING,
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1160): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1160): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1160): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1160): nl80211: Unsubscribe mgmt frames handle 0xb870d718 (mode change)
,D/wpa_supplicant( 1160): nl80211: Subscribe to mgmt frames with non-AP handle 0xb870d718
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb870d718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb870d718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb870d718,
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb870d718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb870d718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb870d718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb870d718
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb870d718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb870d718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Register frame type=0xd0 nl_handle=0xb870d718
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1160): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1160):   * bssid=c0:ff:d4:d3:aa:48,
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
,D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,W/dalvikvm( 4467): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1160): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1160): reply (1045) for get BSS: id=0
,I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1160): freq=5220
I/wpa_supplicant( 1160): level=-51
I/wpa_supplicant( 1160): tsf=0000000108701629
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1160): ssid=NG7005g
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=1
I/wpa_supplicant( 1160): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412,
I/wpa_supplicant( 1160): level=-46
I/wpa_supplicant( 1160): tsf=0000000108701621
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=NG700
I/wpa_supplicant( 1160): ====,
I/wpa_supplicant( 1160): id=2
I/wpa_supplicant( 1160): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-81
I/wpa_supplicant( 1160): tsf=0000000108701645,
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=Gonzos
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=3
I/wpa_supplicant( 1160): bssid=06:7c:34:12:7f:81,
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-85
I/wpa_supplicant( 1160): tsf=0000000108701636
I/wpa_supplicant( 1160): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1160): ssid=UPC Wi-Free
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=4
I/wpa_supplicant( 1160): bssid=64:7c:34:12:7f:81,
I/wpa_supplicant( 1160): freq=2437
I/wpa_supplicant( 1160): level=-84
I/wpa_supplicant( 1160): tsf=0000000108701640
I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1160): ssid=UPC5999698,
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=5
I/wpa_supplicant( 1160): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): freq=2412
I/wpa_supplicant( 1160): level=-47,
I/wpa_supplicant( 1160): tsf=0000000108701609
I/wpa_supplicant( 1160): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1160): ssid=01ABC
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=6,
I/wpa_supplicant( 1160): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1160): freq=2462
I/wpa_supplicant( 1160): level=-88
I/wpa_supplicant( 1160): tsf=0000000108701652
,I/wpa_supplicant( 1160): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1160): ssid=UPC0039325
I/wpa_supplicant( 1160): ====
I/wpa_supplicant( 1160): id=7
I/wpa_supplicant( 1160): bssid=fe:94:e3:11:35:3c
,I/wpa_supplicant( 1160): freq=2462
I/wpa_supplicant( 1160): level=-89
I/wpa_supplicant( 1160): tsf=0000000108701648
I/wpa_supplicant( 1160): flags=
,D/WirelessDisplayService(  910): getDiscoveryDongleList
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 108701629, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 2412, timestamp: 108701621, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 108701645, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 108701636, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 108701640, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -47, frequency: 2412, timestamp: 108701609, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 6: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 108701652, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 7: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 108701648, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 8 to mScanResults
D/BatSI   (  910): WIFI scan stopped for: 640a0300 uid:1000
,D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (8) end of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList
,D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,E/FbInjectorInitializer( 4467): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1160): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1160): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1160): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1160): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1160): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1160): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1160): nl80211: if_removed already cleared - ignore event
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
D/wpa_supplicant( 1160): Add randomness: count=16 entropy=8
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
D/wpa_supplicant( 1160): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1160): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1160): EAPOL: enable timer tick
D/wpa_supplicant( 1160): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1160): htc_wext_set_keepalive +
I/wpa_supplicant( 1160): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1160): getPrivFuncNum +	
I/wpa_supplicant( 1160): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1160): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1160): Get randomness: len=32 entropy=9
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/WifiStateMachine(  910): Associated
,D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
D/WifiStateMachine(  910): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
,D/Tethering(  910): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 1160): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb870d9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1160):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1160): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1160): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f46b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1160):    broadcast key
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1160): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1160): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1160): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1160): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1160): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1160): wlan0: Connect to SSID: NG700
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/wpa_supplicant( 1160): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1160): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1160): set send_ind_to_ndc = 0
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1160): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1160): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1160): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1160): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1160): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1160): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1160): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1160): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1160): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1160): EAPOL authentication completed successfully
I/wpa_supplicant( 1160): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1160): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1160): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1160): nl80211: if_removed already cleared - ignore event
,D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiStateMachine(  910): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 4172): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4172): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/DhcpStateMachine(  910): [StoppedState] Start DHCP
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): Power_Mode_Type mode = 1
,I/wpa_supplicant( 1160): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
,E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP,
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  910):    returned null
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(43fc5f10): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4241a090 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4241a090 target=com.android.internal.util.StateMachine$SmHandler }
I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4467): Verify
,D/WifiService(  910): New client listening to asynchronous messages
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4467): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4467): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 9.508MB for 73240-byte allocation
,D/Process (  910): killProcessQuiet, pid=3829
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 3829:com.htc.mediamanager/u0a32 (adj 15): empty #17
,D/PMS     (  910): acquireWL(440acfb0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2238 10028 null
,D/PMS     (  910): acquireWL(4249d128): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2238 10028 null
,D/PMS     (  910): releaseWL(440acfb0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2238/10028)
,D/GCM     ( 1367): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2238/10028)
,D/PMS     (  910): releaseWL(4249d128): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1403): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1403): Util - no network available!
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1403/10053)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1403/10053)
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 3829
,D/AutoSetting( 1403): service - onCreate()
,D/AutoSetting( 1403): service - AddressCache: using context: com.htc.Weather
,I/ActivityManager(  910): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4496 uid=10078 gids={50078, 3003, 5012}
D/AutoSetting( 1403): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  910): request 423c76d8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1403): service - mHandler: cancel location update
D/AutoSetting( 1403): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4467): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4467): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4467): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/MobileConnectivityChangeReceiver( 4496): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4496): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4496): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4496): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  910): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4519 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4496/10078)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4496/10078)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4496/10078)
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4467): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/dalvikvm( 4467): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4467): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/dalvikvm( 4467): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4467): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4467): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4467): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4467): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4467): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4467): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,D/Process (  910): killProcessQuiet, pid=4224
I/ActivityManager(  910): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4547 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,I/ActivityManager(  910): Killing 4224:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 9.965MB for 84664-byte allocation
,E/dalvikvm( 4467): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4467): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4467): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,I/ActivityManager(  910): Recipient 4224
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4547): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/WifiService(  910): Client connection lost with reason: 4
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4547): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 9.976MB for 28144-byte allocation
W/dalvikvm( 4467): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4467): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4467): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/GAV2    ( 4547): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/dalvikvm( 4467): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4467): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4467): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,W/ContextImpl( 4547): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4547): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 10.018MB for 39954-byte allocation
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1160): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -46 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/PMS     (  910): releaseWL(43fc5f10): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): gateway: /192.168.1.1
D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1160): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
,D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -46, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1120): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
I/dalvikvm-heap( 4467): Grow heap (frag case) to 10.093MB for 79892-byte allocation
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=20445 delay=15s
,I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  910): WAN detection
V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
D/MDST    (  910): default: setTeardownRequested(true)
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1120): WifiActivity: 1
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/MDST    (  910): default: setTeardownRequested(true)
,D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/WISPrService( 4172): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@4245c4f8
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  358): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    (  358): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    (  358): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    (  358): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    (  358): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    (  358): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  910): handleConnectivityChange: resetting
,D/libc    (  358): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  910): acquireWL(431dfd00): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,I/QuickSettingWifi( 1120): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4496/10078)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4547/10151)
D/PMS     (  910): acquireWL(43924370): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2238 10028 null
,D/PMS     (  910): acquireWL(43cc9018): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2238 10028 null
,I//system/bin/ip(  358): RTNETLINK answers: No such file or directory
,I/logwrapper(  358): /system/bin/ip terminated by exit(254)
D/PMS     (  910): releaseWL(43924370): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,V/WebViewChromiumFactoryProvider( 4547): Binding Chromium to main looper Looper (main, tid 1) {41b31240}
,I/CheckinService( 2238): Preparing to send checkin request
,I/EventLogService( 2238): Accumulating logs since 1451956816778
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2238/10028)
I/LibraryLoader( 4547): Expected native library version number "",actual native library version number ""
I/chromium( 4547): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4547): Initializing chromium process, renderers=0
I//system/bin/ip(  358): RTNETLINK answers: No such process
,I/logwrapper(  358): /system/bin/ip terminated by exit(2)
,E/AudioManagerAndroid( 4547): BLUETOOTH permission is missing!
D/PMS     (  910): acquireWL(440fe9c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 365 1013 null
D/PMS     (  910): acquireWL(42683538): PARTIAL_WAKE_LOCK  AudioMix 0x1 365 1013 null
D/PMS     (  910): releaseWL(42683538): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/GoogleHttpClient( 2238): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2238): Using GMS GoogleHttpClient
D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,I/Adreno-EGL( 4547): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4547): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4547): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4547): Local Branch: 
I/Adreno-EGL( 4547): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4547): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4547):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  910): releaseWL(431dfd00): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2238/10028)
,D/ConnectivityService(  910): getNetworkInfo networkType=0 called by com.google.android.gms (2238/10028)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 10.281MB for 75760-byte allocation
,I/NSApplication( 4547): Starting up...
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4547/10151)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4547/10151)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{437cea30 u0 ReceiverList{4379cd80 4467 com.facebook.katana/10026/u0 remote:43764110}}
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{437cea30 u0 ReceiverList{4379cd80 4467 com.facebook.katana/10026/u0 remote:43764110}}
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4400e818 u0 ReceiverList{4400e7b8 4467 com.facebook.katana/10026/u0 remote:43fec208}}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4144/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4144/10160)
,D/Process (  910): killProcessQuiet, pid=4252
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
I/ActivityManager(  910): Killing 4252:com.google.android.partnersetup/u0a31 (adj 15): empty #17
W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
I/ActivityManager(  910): Recipient 4252
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1823/10178)
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1823/10178)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1823/10178)
,D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1584): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2238): awaiting user notification for token
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41c71450 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 8 2 12
D/PMS     (  910): acquireWL(42e2deb8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1429 10028 null
D/PMS     (  910): releaseWL(42e2deb8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/wpa_supplicant( 1160): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1160): EAPOL: disable timer tick
,I/ActivityManager(  910): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4605 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4605): install
,I/MultiDex( 4605): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4605): loading existing secondary dex files
,I/MultiDex( 4605): load found 1 secondary dex files
,I/MultiDex( 4605): install done
,I/ProviderInstaller( 4605): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/GCoreFlp( 1429): Unknown pending intent to remove.
D/PMS     (  910): acquireWL(44046478): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1429 10028 null
D/PMS     (  910): releaseWL(44046478): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4467): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4467): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4605/10028)
,D/WIFI_ICON( 1120): WifiActivity: 3
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/PMS     (  910): releaseWL(425da820): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  910): NoActiveNetworkState
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4282/10100)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10075)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1429/10028)
,V/Tethering(  910): bSetPropertyMultiRAB:false
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  910): Found interface wlan0
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
I/NetworkMonitor( 3847): type=WIFI subType= reason=null isConnected=true
I/acms    ( 1883): Checking Certificates
I/acms    ( 1883): Checking Developer Certificates
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): CONNECTED
,I/acms    ( 1883): Checking Application Certificates
I/acms    ( 1883): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
,I/acms    ( 1883): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1883): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1883): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1883): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (3847/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4496/10078)
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1823/10178)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.musicenhancer (3869/10051)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1883/1000)
I/acms    ( 1883): Updating next query delay: 75600000
I/mlserverapp( 1883): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1883): cancelACMSProgrammedChecks
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/PMS     (  910): acquireWL(43fe1980): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4282/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43fb5ad8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): releaseWL(43fb5ad8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  910): releaseWL(43fe1980): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (2451/10021)
,I/Adreno-EGL( 4605): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4605): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4605): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4605): Local Branch: 
I/Adreno-EGL( 4605): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4605): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4605):                  aa63bbd948f41d15fc72f585e
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(41e22e10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2238 10028 null
D/PMS     (  910): releaseWL(41e22e10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1367): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
D/PMS     (  910): acquireWL(42690998): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1367 10028 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2238/10028)
,D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1367): [NET] getaddrinfo-,err=8
D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1367): [NET] getaddrinfo-, 1
,D/libc    ( 1367): [NET] getaddrinfo_proxy+
D/libc    (  358): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  358): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  358): [NET] +++++ res_nsend xid =fe0a +++++
D/libc    (  358): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  358): [NET] NOT IN CACHE
,D/AutoSetting( 1403): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4496): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4496): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1403/10053)
,D/AutoSetting( 1403): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1403): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1403): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1403): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1403): service - handleMessage() setting current location null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4547/10151)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/AutoSetting( 1403): Util - check NLP state, Allowned:false, Enabled:false
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1403): service - onStartCommand() check timezone in 30000
,W/Settings( 4605): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1403/10053)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4144/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4144/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1823/10178)
,D/libc    (  358): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 217
D/libc    (  358): [NET]res_nsend:resplen=79
D/libc    (  358): [NET]res_queryN: exit 3, ancount=2
D/libc    (  358): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  358): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1367): [NET] getaddrinfo_proxy-, success
,I/dalvikvm-heap( 4144): Grow heap (frag case) to 13.500MB for 1821008-byte allocation
,D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1367): [NET] getaddrinfo-,err=8
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
D/PMS     (  910): acquireWL(43d97ef8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
D/PMS     (  910): releaseWL(43d97ef8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/Adreno-EGL( 4605): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4605): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4605): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4605): Local Branch: 
I/Adreno-EGL( 4605): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4605): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4605):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4605): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4605): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4605): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4605): Local Branch: 
I/Adreno-EGL( 4605): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
,I/Adreno-EGL( 4605): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4605):                  aa63bbd948f41d15fc72f585e
,D/GCM     ( 1367): Connected
D/PMS     (  910): acquireWL(42dd0e20): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10028 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
,I/CheckinTask( 2238): Sending checkin request (8892 bytes)
D/libc    ( 2238): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2238): [NET] getaddrinfo-,err=8
D/libc    ( 2238): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2238): [NET] getaddrinfo-, 1
D/libc    ( 2238): [NET] getaddrinfo_proxy+
D/libc    (  358): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  358): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  358): [NET] +++++ res_nsend xid =c99d +++++
D/libc    (  358): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  358): [NET] NOT IN CACHE
D/PMS     (  910): releaseWL(42690998): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1367/10028)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
D/PMS     (  910): releaseWL(42dd0e20): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  910): acquireWL(4250fd50): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10028 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1367/10028)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1367): Message class mpf
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1367/10028)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
D/PMS     (  910): acquireWL(42632218): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
D/PMS     (  910): releaseWL(4250fd50): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  910): releaseWL(42632218): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  358): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 198
D/libc    (  358): [NET]res_nsend:resplen=84
D/libc    (  358): [NET]res_queryN: exit 3, ancount=2
D/libc    (  358): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2238): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2238): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2238): [NET] getaddrinfo-,err=8
,I/PMS     (  910): Going to sleep due to screen timeout...
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421afcc0
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421afcc0, eanble = 0, strlen(mName) = 59
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  910): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42380ae0
W/SensorService(  910): Listener[1] = com.htc.smartdim.sensor_eye@425f1d38
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  910): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  910): Couldn't get kernel wake lock stats
V/LightsService(  910): setLight #2: color=#0
D/qdlights(  910): set_light_buttons_func: on=0 brightness=0
V/LightsService(  910): setLight #0: color=#0
,D/WirelessDisplayService(  910): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  910): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  910): mWirelessDisplayManager is null
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=4 [23][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(423773f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
D/PMS     (  910): releaseWL(423773f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2238/10028)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getNetworkInfo networkType=0 called by com.google.android.gms (2238/10028)
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2238): awaiting user notification for token
D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1584): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41cdf970 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 5 2 12
,D/SurfaceControl(  910): Excessive delay in blankDisplay() while turning screen off: 385ms
D/NfcService( 1259): ScreenObserver: OFF
,D/NfcService( 1259): applyRouting - 0
D/PMS     (  910): nativeSetInteractive:false
D/PMS     (  910): nativeSetInteractive:false done
D/PMS     (  910): nativeSetAutoSuspend:true
D/PMS     (  910): nativeSetAutoSuspend:true done
D/HABCtrl (  910): TPE algorithm. remove timeout.
D/PMS     (  910): OOBE c monitor 11
I/InputMethodManagerService(  910): screenObserver, isScreenOn=false
I/InputManager(  910): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  910): Disable input method client, pid=4396
D/NfcService( 1259): applyRouting -2
I/IntentController( 1120): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  910): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@431208b0)
D/PMS     (  910): acquireWL(4264ab28): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
D/PMN     (  910): wakingUp
D/PMS     (  910): releaseWL(4264ab28): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  910): **** SHOWN CALLED ****
D/PMS     (  910): acquireWL(44076f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/WindowManager(  910): No lock screen! windowToken=null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(44076f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMN     (  910): onScreenOn
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/MtpService( 2451): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2451): [MTP][onReceive]-
D/NfcService( 1259): applyRouting - 0
,D/AutoSetting( 1403): receiver - intent: android.intent.action.USER_PRESENT
D/WirelessDisplayService(  910): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/NfcService( 1259): applyRouting -2
D/PMS     (  910): acquireWL(435916c8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,D/PMS     (  910): releaseWL(435916c8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -46 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  910): BroadcastRSSIForIMS, newrssi =-46 , oldRssi= -200
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_ON
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  910): ACTION_SCREEN_ON
I/AlarmManager(  910): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done recovering
I/AlarmManager(  910): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  910): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiDataStallTracker(  910): startDataStallAlarm: tag=20446 delay=15s
D/AutoSetting( 1403): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
I/ClockThread( 1120): stop update clock
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): SET_SCREEN_ON:On
I/wpa_supplicant( 1160): htc_wext_set_keepalive +
I/wpa_supplicant( 1160): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1160): getPrivFuncNum +	
I/wpa_supplicant( 1160): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1160): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  910):    returned true
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,I/CheckinTask( 2238): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2238): Unable to close GMS GoogleHttpClient
D/WIFI_ICON( 1120): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -46 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
D/TetherSettings( 4172): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4172): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4172): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4172): Cust_ConnectToPC   : spcsc>false
D/        ( 4172): Cust_ConnectToPC   : IPT>true
D/        ( 4172): Cust_ConnectToPC   : Singel_USB>false
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1160): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,W/Settings( 4172): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/SRS_Proc(  365): ParamSet string: screen_state=on
,E/SmartNS_Utility( 4172): hasRemovableStorageSlot: true
,D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WIFI_ICON( 1120): WifiActivity: 1
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2238/10028)
D/SmartNS_Utility( 4172): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4172): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4172): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 4172): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4172): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4172): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4172):  defaultType:0
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
D/WIFI_ICON( 1120): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/NetworkPolicy(  910): updateScreenOn: false
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2238/10028)
,I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4649 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  910): releaseWL(43cc9018): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 2238): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41e24e08 that was originally bound here
E/ActivityThread( 2238): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41e24e08 that was originally bound here
E/ActivityThread( 2238): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2238): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2238): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2238): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2238): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2238): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2238): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2238): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2238): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2238): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2238): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2238): 	at bks.a(SourceFile:298)
E/ActivityThread( 2238): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2238): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2238): 	at java.lang.Thread.run(Thread.java:864)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,W/ContextImpl( 4649): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
D/PMS     (  910): acquireWL(43c34e08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1429 10028 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1786): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1786): onScreenOn: 1451956872922
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1786): onScreenOn: 1451956872922
D/PMS     (  910): releaseWL(43c34e08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42380ae0
,W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  910): pid=910, uid=1000
,W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42380ae0, eanble = 0, strlen(mName) = 91
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  910): Listener[0] = com.htc.smartdim.sensor_eye@425f1d38
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SmartSyncUtils( 4649): isEpsOn(), nState = 0
D/PMN     (  910): goingToSleep
D/PMS     (  910): acquireWL(43556078): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4649 1000 null
D/PMS     (  910): acquireWL(43b85ad8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 910 1000 null
,D/PMS     (  910): releaseWL(43556078): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/AlarmManager(  910): ACTION_SCREEN_OFF
I/AlarmManager(  910): [AlarmQueuing] screen off now: 
I/AlarmManager(  910): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20446 mDataStallAlarmIntent=PendingIntent{43ffda38: PendingIntentRecord{425e9478 android broadcastIntent}}
I/AlarmManager(  910): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1160): SET_SCREEN_ON:Off
I/wpa_supplicant( 1160): htc_wext_set_keepalive +
I/wpa_supplicant( 1160): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1160): getPrivFuncNum +	
I/wpa_supplicant( 1160): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1160): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1160): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1160): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1160): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  365): ParamSet string: screen_state=off
,D/PMS     (  910): acquireWL(435e4900): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 910 1000 null
,D/SmartSyncUtils( 4649): getMobilePolicyEnabled, result = true
,D/Process (  910): killProcessQuiet, pid=4282
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/fb4a(:<default>):UserScope( 4467): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  910): Killing 4282:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/NetworkPolicy(  910): updateScreenOn: false
W/fb4a(:<default>):UserScope( 4467): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/wpa_supplicant( 1160): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
I/ActivityManager(  910): Recipient 4282
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(435e4900): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,I/GCM     ( 1367): GCM config loaded
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 4649): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/ContactMessageStore( 1248): start background delete task...
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/ContactMessageStore( 1248): size: 0 , 0
,D/ContactMessageStore( 1248): Background delete complete
,D/SmartSyncUtils( 4649): isEpsOn(), nState = 0
D/SmartSyncUtils( 4649): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4649): getMobilePolicyEnabled, result = true
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
D/WifiService(  910): New client listening to asynchronous messages
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425f1d38
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 1
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425f1d38, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 0
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425f1d38, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425f1d38
E/ActivityThread(  910): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4259a880 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4259a880 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  910): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  910): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  910): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  910): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  910): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  910): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  910): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  910): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  910): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  910): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  910): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  910): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  910): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] getTotalRam: 1873 Mb
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1786): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1786): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1786): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1786): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1786): onScreenOff
D/PMS     (  910): acquireWL(44092720): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1429 10028 null
D/PMS     (  910): releaseWL(44092720): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/AutoSetting( 1403): service - mHandler: cancel location update
,D/AutoSetting( 1403): service -           changes count: 0
,E/fb4a(:<default>):LocalFbBroadcastManager( 4467): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  358): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  358): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  358): [NET] +++++ res_nsend xid =90c0 +++++
D/libc    (  358): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  358): [NET] NOT IN CACHE
,D/libc    (  358): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  358): [NET]res_nsend:resplen=172
D/libc    (  358): [NET]res_queryN: exit 3, ancount=4
D/libc    (  358): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/104.81.130.175
,D/PMS     (  910): releaseWL(440fe9c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/ActivityManager(  910): Activity pause timeout for ActivityRecord{41dff7e0 u0 com.test.thalitest/.MainActivity t2}
,D/ContactMessageStore( 1248): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1248): MSG_NOTIFY_CS_TO_SYNC <<
,I/GAV2    ( 4547): Thread[GAThread,5,main]: No campaign data found.
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,I/jxcore-log( 4396): Test app app.js loaded
I/jxcore-log( 4396): 
,I/Choreographer( 4396): Skipped 513 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4396): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4396): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b392a0 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 4396): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/PMS     (  910): acquireWL(42e08698): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1429 10028 null
D/PMS     (  910): acquireWL(43566ac8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1429 10028 null
D/PMS     (  910): releaseWL(43b85ad8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/PMS     (  910): releaseWL(42e08698): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  910): releaseWL(43566ac8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/Process (  910): killProcessQuiet, pid=4305
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4305:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4305
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1478): service - handleMessage() stop self
,D/AutoSetting( 1478): service - onDestroy() END
,D/Process (  910): killProcessQuiet, pid=4269
,D/AutoSetting( 1478): service - handleMessage() quit looper
,I/ActivityManager(  910): Killing 4269:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4269
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{440f8e10 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(426a2070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): releaseWL(426a2070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1403): service - mHandler: update timezone
,D/AutoSetting( 1478): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1478): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1478): service - onCreate()
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1478): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1478): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1584): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1584): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1478): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1478): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1478): service - mHandler: update timezone
,D/AutoSetting( 1478): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1478): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1478): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1478): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1584): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1120): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41e4b138 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.htc.htclocationservice 2 7 2 11
,D/PMS     (  910): acquireWL(435bd870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10028}
,V/AlarmManager(  910): sending alarm PendingIntent{440d38a0: PendingIntentRecord{4250a558 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142336, Int=0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
,D/PMS     (  910): releaseWL(435bd870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  910): acquireWL(44002240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
,D/PMS     (  910): releaseWL(44002240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1403): service - handleMessage() stop self
,D/AutoSetting( 1403): service - handleMessage() quit looper
,D/AutoSetting( 1403): service - onDestroy() END
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  910): killProcessQuiet, pid=3869
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3869:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3869
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{425958a0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  910): acquireWL(43e1f580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=159260, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43e1f580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1478): service - handleMessage() stop self
,D/AutoSetting( 1478): service - onDestroy() END
,D/AutoSetting( 1478): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4323
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4323:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4323
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(4404afb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(4404afb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1248): switchBindHtcMsgCursor: null
,D/PMS     (  910): acquireWL(42c2bcb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42c2bcb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(440624f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=219260, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(440624f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43632710): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10026}
,V/AlarmManager(  910): sending alarm PendingIntent{4263a7b8: PendingIntentRecord{435ae760 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229759, Int=0
,I/ActivityManager(  910): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4685 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  910): sending alarm PendingIntent{426103c0: PendingIntentRecord{426af850 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1451956982098, Int=10800000
,D/PMS     (  910): releaseWL(43632710): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.aurora (4685/10047)
,I/ActivityManager(  910): Killing 4340:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=4340
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4340
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2238/10028)
,D/PMS     (  910): acquireWL(44059ba0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(44059ba0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  910): acquireWL(434cb0b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10026}
,V/AlarmManager(  910): sending alarm PendingIntent{43f8c8a8: PendingIntentRecord{435ae760 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=232210, Int=0
,D/PMS     (  910): releaseWL(434cb0b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(4394ca10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4394ca10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  910): acquireWL(440bc218): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=279260, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(440bc218): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(43ff9fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43ff9fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(4321ce48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(4321ce48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4439a9e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=339259, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4439a9e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(4430ba10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4430ba10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1584): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1584): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1120): com.google.android.gms (false,0)
,W/GLSActivity( 1367): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1367): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1367): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1367): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1367): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1367): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1367): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1367): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41ebc098 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4108): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4108): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4108): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4108): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4108): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4108): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4108): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4108): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1120): com.google.android.gms 1 9 3 12
,D/libc    ( 4108): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4108): [NET] getaddrinfo-,err=8
D/libc    ( 4108): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4108): [NET] getaddrinfo-, 1
,D/libc    ( 4108): [NET] getaddrinfo_proxy+
D/libc    (  358): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  358): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  358): [NET] +++++ res_nsend xid =5149 +++++
D/libc    (  358): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  358): [NET] NOT IN CACHE
,D/libc    (  358): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 8
D/libc    (  358): [NET]res_nsend:resplen=87
D/libc    (  358): [NET]res_queryN: exit 3, ancount=2
D/libc    (  358): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  358): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4108): [NET] getaddrinfo_proxy-, success
I/global  ( 4108): call createSocket() return a new socket.
D/libc    ( 4108): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4108): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4108): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4108): [NET] getaddrinfo-,err=8
,D/PMS     (  910): acquireWL(43fe18e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
,D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(43fe18e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(4367f3f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=399260, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4367f3f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(436657c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10026}
,V/AlarmManager(  910): sending alarm PendingIntent{44048c78: PendingIntentRecord{432c07c0 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=411872, Int=300000
,V/AlarmManager(  910): sending alarm PendingIntent{4327b260: PendingIntentRecord{422499a0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1451957090885, Int=1800000
,D/PMS     (  910): acquireWL(436639e0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2238 10028 null
,D/PMS     (  910): releaseWL(436657c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  910): acquireWL(4363a110): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2238 10028 null
,D/PMS     (  910): releaseWL(436639e0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 2238): Aggregate from 1451956870361 (log), 1451955290817 (data)
,D/PMS     (  910): releaseWL(4363a110): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(43625698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43625698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(435d9a58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=459259, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(435d9a58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(4356a7f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(4356a7f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(42e7c810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42e7c810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=100
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(4240a228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=519259, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4240a228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(4204bf00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/PMS     (  910): releaseWL(4204bf00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(423eb408): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=579260, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(423eb408): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(421828e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(421828e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(424b5338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(424b5338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1248): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1248): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1248): sku_id=99
D/ContactMessageStore( 1248): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1248): start background delete task...
D/ContactMessageStore( 1248): size: 0 , 0
,D/ContactMessageStore( 1248): Background delete complete
,D/PMS     (  910): acquireWL(4246aaf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=639260, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4246aaf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(41caae58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(41caae58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4304b730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(4304b730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(41da6bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=699259, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(41da6bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(425bc210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(425bc210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/Process (  910): killProcessQuiet, pid=4354
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4354:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4354
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(424464f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  910): releaseWL(424464f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(424fcbf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=759259, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(424fcbf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43df8f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43df8f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(425e9cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10026}
,V/AlarmManager(  910): sending alarm PendingIntent{44048c78: PendingIntentRecord{432c07c0 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=711872, Int=300000
,V/AlarmManager(  910): sending alarm PendingIntent{41d76c60: PendingIntentRecord{42466cb0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786652, Int=0
,D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
,D/PMS     (  910): releaseWL(425e9cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  910): Done.
,D/ConnectivityService(  910): Setting timer for 720seconds
,D/PMS     (  910): acquireWL(42594918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42594918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42638828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=819259, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42638828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42e9b4f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42e9b4f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42377240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42377240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(4348e5a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=879259, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4348e5a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43cafb58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43cafb58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(434df810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
,D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(434df810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(435ca590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=939260, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(435ca590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4256e9b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(4256e9b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43bc74e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=999259, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43bc74e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(440dbd98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10028}
,V/AlarmManager(  910): sending alarm PendingIntent{43fb5a68: PendingIntentRecord{42510888 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1010980, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{42488c80: PendingIntentRecord{423b0040 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1451957702416, Int=900000
D/PMS     (  910): acquireWL(43c68de0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1367 10028 null
,V/AlarmManager(  910): sending alarm PendingIntent{44033ff0: PendingIntentRecord{4311c2c8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1451957773039, Int=0
,D/PMS     (  910): releaseWL(43c68de0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  910): acquireWL(43186098): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
,D/PMS     (  910): releaseWL(43186098): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/ContextImpl( 4649): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4649): call getInstance()
,D/SmartSyncUtils( 4649): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4649): MY_DEBUG = false
,D/PMS     (  910): acquireWL(440ea938): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4649 1000 null
,D/PMS     (  910): releaseWL(440dbd98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4649): [updateNmRange] bManual = false
,D/PMS     (  910): acquireWL(42572ac8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10028 null
D/SmartSyncScreenOnOffTimeReceiver( 4649): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 2, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4649): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4649): SettingOnTime = 1452042000000, randomSettingOnTime = 1452039170000
D/SmartSyncScreenOnOffTimeReceiver( 4649): SettingOffTime = 1452038400000, randomSettingOffTime = 1452038409000
,D/SmartSyncScreenOnOffTimeReceiver( 4649): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4649): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4649): bNightModeTurnOffOnce = false
W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): releaseWL(440ea938): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/GCM     ( 1367): Message class mow
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1367/10028)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1367/10028)
,D/PMS     (  910): releaseWL(42572ac8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  910): acquireWL(4263bc30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
,D/PMS     (  910): releaseWL(4263bc30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=7 [226][18][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(436306a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(436306a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(44333868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(44333868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(44013400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1059260, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(44013400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(440127a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(440127a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43ded340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(43ded340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43b1c3b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1119259, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43b1c3b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43b165c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(43b165c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43625698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43625698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(435a05d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1179260, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(435a05d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4356a7f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(4356a7f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(430a3e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41ca7778: PendingIntentRecord{424c8458 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1203261, Int=0
,D/PMS     (  910): acquireWL(4308ddd0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 910 1000 null
,D/PMS     (  910): releaseWL(430a3e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(42e76028): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=8 [34][3][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1160): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1160): nl80211: survey data missing!
E/wpa_supplicant( 1160): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1160): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(4215d418): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 910 1000 WorkSource{10160}
,D/PMS     (  910): releaseWL(4308ddd0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  910): releaseWL(42e76028): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(41f975a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(41f975a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(425cab58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(425cab58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/dalvikvm-heap( 4144): Grow heap (frag case) to 15.197MB for 1821008-byte allocation
,I/dalvikvm-heap( 4144): Grow heap (frag case) to 16.955MB for 1821008-byte allocation
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(42394178): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(4215d418): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
,D/PMS     (  910): releaseWL(42394178): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  910): acquireWL(440c26e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(440c26e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(434722e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41ca7778: PendingIntentRecord{424c8458 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1233354, Int=0
,D/PMS     (  910): acquireWL(426708d8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 910 1000 null
,D/PMS     (  910): releaseWL(434722e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(41efa0b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(426708d8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  910): releaseWL(41efa0b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  910): acquireWL(4356c088): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1239260, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4356c088): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42529660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(42529660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,D/PMS     (  910): acquireWL(424d4e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(424d4e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42b1e6f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1299259, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42b1e6f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42679238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42679238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42518a90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42518a90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42366ed0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1359259, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42366ed0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43c0c3c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43c0c3c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(424ba5c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(424ba5c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(4334d668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1419259, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4334d668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42490000): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderNotification, total:1
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(42490000): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
V/NotificationService(  910): batLight: plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c80000
D/qdlights(  910): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PowerUI ( 1120): closing low battery warning: level=98
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HeadsetPhoneState( 1646): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/ContextImpl( 4649): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4172): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4172): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4172): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4172): Cust_ConnectToPC   : spcsc>false
D/        ( 4172): Cust_ConnectToPC   : IPT>true
D/        ( 4172): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4172): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4172): Index of the first 1 = -1
W/Settings( 4172): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4172): hasRemovableStorageSlot: true
I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
D/SmartNS_Utility( 4172): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4172): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4172): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,W/ContextImpl( 4172): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 4172): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  910): acquireWL(41fa8408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(41fa8408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=98
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43304f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1479259, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43304f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4430ba50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4430ba50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=98
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4328dfa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4328dfa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=98
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4400e638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1539260, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4400e638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42593518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42593518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(426b0f08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(426b0f08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=98
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(432b15c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1599259, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(432b15c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4372a428): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4372a428): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43df98f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43df98f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=98
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4256a2d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1659259, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4256a2d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43569a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=99
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(43569a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4368fae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4368fae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42360d50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1719259, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42360d50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42af3630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42af3630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43696778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  910): sending alarm PendingIntent{41d76c60: PendingIntentRecord{42466cb0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1506685, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{437e8ea8: PendingIntentRecord{42660e58 com.android.vending startService}}, i=null, t=0, cnt=1, w=1451958534729, Int=0
,D/PMS     (  910): releaseWL(43696778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/ConnectivityService(  910): Done.
,D/ConnectivityService(  910): Setting timer for 720seconds
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4108): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4108): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4108): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4108): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4108): [1] DailyHygiene.reschedule: Scheduling new run in 90 minutes (failures=3)
,D/PMS     (  910): acquireWL(423c17f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1779259, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(423c17f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(425e8c60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10073}
,V/AlarmManager(  910): sending alarm PendingIntent{42e7bb20: PendingIntentRecord{43982ef0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1451958549913, Int=0
,D/PMS     (  910): releaseWL(425e8c60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4108): [1] 5.onFinished: Installation state replication succeeded.
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): acquireWL(43fc0b80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43fc0b80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(440bdc80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1839259, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  910): Prepared write state in 49ms
,D/PMS     (  910): releaseWL(440bdc80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  910): Pruning old procstats: /data/system/procstats/state-2016-01-04-06-42-34.bin
,D/PMS     (  910): acquireWL(435694c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/DotMatrix( 1584): [EventService] reorderNotification, total:0
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 1646): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck,
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PMS     (  910): releaseWL(435694c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/ContextImpl( 4649): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4172): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4172): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4172): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4172): Cust_ConnectToPC   : spcsc>false
D/        ( 4172): Cust_ConnectToPC   : IPT>true
,D/        ( 4172): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4172): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4172): Index of the first 1 = -1
W/ContextImpl( 4172): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4172): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4172): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4172): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4172): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4172): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42fa1720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42fa1720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(441115a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41bfc1b0: PendingIntentRecord{41bf87e0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1899259, Int=0
,D/Process (  910): killProcessQuiet, pid=3993
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  910): Killing 3993:com.google.android.gm/u0a107 (adj 15): empty for 1823s
I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(441115a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
I/ActivityManager(  910): Recipient 3993
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4761): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4761): ====startRecUseTime====
D/htc.customization.log.level( 4761):  is 
W/CustomizationLogLevel( 4761): Level value is invalid, use default level 2
D/CustomizationManager( 4761):  Read ACC file spent 0.100 (s)
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4761): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4761): Parsing tag category name = system
I/CustomizationCIDLoader( 4761): Parsing tag category name = application
I/CustomizationCIDLoader( 4761): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4761): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4761): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4761): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4761): Parsing tag category name = Settings
D/CustomizationManager( 4761):  Read CID file spent 0.150 (s)
D/CustomizationManager( 4761):  All configurations done spent 0.150 (s)
W/HtcNativeFlag( 4761): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4761): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4761): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4761): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  910): deletePackageAsUser: pkg=com.test.thalitest, pid=4761, uid=2000 user=0
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  910): killProcessQuiet, pid=4396
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  910): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  910): Killing 4396:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
D/Process (  910): killProcessQuiet, pid=4547
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  910): killProcessQuiet, pid=4519
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  910): killProcessQuiet, pid=4496
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  910): killProcessQuiet, pid=3847
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  910): killProcessQuiet, pid=4444
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  910): Killing 4547:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1803s
I/ActivityManager(  910): Killing 4519:com.android.chrome/u0a96 (adj 15): empty for 1803s
I/ActivityManager(  910): Killing 4496:com.google.android.setupwizard/u0a78 (adj 15): empty for 1803s
I/ActivityManager(  910): Killing 3847:com.google.android.music:main/u0a154 (adj 15): empty for 1803s
I/ActivityManager(  910): Killing 4444:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1809s
I/ActivityManager(  910):   Force finishing activity ActivityRecord{41dff7e0 u0 com.test.thalitest/.MainActivity t2}
I/ActivityManager(  910): Recipient 4496
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4444
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4519
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  910): Skipping PackageSetting{422b5668 com.example.hello/10356} due to missing metadata
E/JavaBinder(  910): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  910): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  910): Got RemoteException sending setActive(false) notification to pid 4396 uid 10348
E/JavaBinder( 1213): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  910): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  910): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  910): Client com.google.android.music (pid 3847): Died!
I/ActivityManager(  910): Recipient 3847
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  910): WIN DEATH: Window{42518f68 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  910): Client connection lost with reason: 4
I/ActivityManager(  910): Recipient 4547
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/DotMatrix( 1584): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1584): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1584): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1883): Unregistering com.test.thalitest
E/acms    ( 1883): Could not unregister removed application com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1429): Ignoring removeGeofence because network location is disabled.
W/BroadcastQueue(  910): Failure sending broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
W/BroadcastQueue(  910): android.os.DeadObjectException
W/BroadcastQueue(  910): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  910): 	at android.content.IIntentReceiver$Stub$Proxy.performReceive(IIntentReceiver.java:124)
W/BroadcastQueue(  910): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:457)
W/BroadcastQueue(  910): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:564)
W/BroadcastQueue(  910): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:636)
W/BroadcastQueue(  910): 	at com.android.server.am.BroadcastQueue$1.handleMessage(BroadcastQueue.java:147)
W/BroadcastQueue(  910): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  910): 	at android.os.Looper.loop(Looper.java:157)
W/BroadcastQueue(  910): 	at com.android.server.am.ActivityManagerService$AThread.run(ActivityManagerService.java:2098)
D/PMS     (  910): acquireWL(435d04a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1429 10028 null
D/PMS     (  910): releaseWL(435d04a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1333): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1333): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
D/VoicemailCleanupService( 1300): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1259): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
D/AccTypeManager( 1333): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/Launcher( 1274): Deferring update until onResume
D/Launcher( 1274): waitUntilResume // bindAppsRemoved
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
D/PackageBroadcastService( 2238): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/InputMethodManagerService(  910): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/ActivityManager(  910): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4776 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
E/ExternalAccountType( 1333): Unsupported attribute readOnly
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/ActivityManager(  910): Delaying start of: ServiceRecord{4410d458 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/MultiDex( 4776): install
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/MultiDex( 4776): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/MultiDex( 4776): loading existing secondary dex files
I/MultiDex( 4776): load found 1 secondary dex files
I/MultiDex( 4776): install done
I/ActivityManager(  910): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4792 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/PhoneApp( 1248): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 2238): CP2 sync disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2238, uid=10028, userID:0
D/PMS     (  910): acquireWL(43fe1890): PARTIAL_WAKE_LOCK  Icing 0x1 2238 10028 null
I/Icing   ( 2238): doRemovePackageData com.test.thalitest
D/PMS     (  910): releaseWL(43fe1890): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ProviderInstaller( 4776): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  910): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4792): install
I/MultiDex( 4792): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4792): loading existing secondary dex files
I/MultiDex( 4792): load found 1 secondary dex files
I/MultiDex( 4792): install done
I/ProviderInstaller( 4792): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  910): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1403): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  910): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  910): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1403): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1274): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2896): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  910): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4814 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/PMS     (  910): acquireWL(42e9b770): PARTIAL_WAKE_LOCK  Icing 0x1 2238 10028 null
I/IcingCorporaProvider( 2896): UpdateCorporaTask done [took 157 ms] updated apps [took 157 ms] 
E/SQLiteLog( 4776): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4776): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca67860
E/DriveAsyncService( 4776): disk I/O error (code 3850)
E/DriveAsyncService( 4776): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4776): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4776): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4776): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4776): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4776): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4776): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4776): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4776): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4776): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4776): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4776): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4776): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/PackageManager(  910): Unable to load service info ResolveInfo{426139c0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  910): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  910): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  910): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  910): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  910): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  910): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteLog( 4776): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 4776): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca67860
E/DocListDatabase( 4776): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4776): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4776): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4776): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4776): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4776): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4776): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4776): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4776): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4776): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4776): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4776): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4776): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4776): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4776): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4776): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4776): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4776): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4776): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4776): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4776): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4776): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4776): threadid=1: thread exiting with uncaught exception (group=0x416fce30)
E/AndroidRuntime( 4776): FATAL EXCEPTION: main
E/AndroidRuntime( 4776): Process: com.google.android.gms.drive, PID: 4776
E/AndroidRuntime( 4776): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4776): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4776): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4776): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4776): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4776): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4776): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4776): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4776): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4776): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4776): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4776): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4776): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4776): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4776): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4776): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4776): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4776): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4776): 	... 10 more
E/ActivityManager(  910): App crashed! Process: com.google.android.gms.drive
D/Process ( 4776): killProcess, pid=4776
D/Process ( 4776): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  910): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  910): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  910): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  910): 	... 5 more
D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  910): start
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4776
I/ActivityManager(  910): Process com.google.android.gms.drive (pid 4776) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
E/SQLiteDatabase( 4814): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4814): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4814): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4814): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4814): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4814): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4814): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4814): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4814): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4814): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4814): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4814): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4814): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4814): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4814): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4814): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4814): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4814): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4814): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4814): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4814): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4814): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4814): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4814): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4814): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4814): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4814): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4814): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4814): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4814): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4814): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4814): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4814): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4814): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4814): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4814): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4814): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4814): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4814): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4814): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4814): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4814): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4814): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4814): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4814): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4814): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4814): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4814): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4814): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4814): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4814): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4814): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4814): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4814): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4814): Opened ClientFlag.db in read-only mode
W/AtomicFile(  910): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
E/SQLiteDatabase( 4814): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4814): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4814): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4814): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4814): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4814): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4814): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4814): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4814): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4814): threadid=11: thread exiting with uncaught exception (group=0x416fce30)
W/AppWidgetServiceImpl(  910): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/AndroidRuntime( 4814): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4814): Process: com.google.android.apps.docs, PID: 4814
E/AndroidRuntime( 4814): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4814): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4814): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4814): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4814): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4814): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4814): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4814): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  910): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  910): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  910): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  910): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  910): 	... 5 more
E/SQLiteDatabase( 4814): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4814): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4814): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4814): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4814): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4814): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4814): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4814): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4814): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4814): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4814): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4814): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4814): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4814): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4814): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4814): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4814): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4814): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4814): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4814): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4814): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4814): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4814): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4814): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4814): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4814): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4814): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4814): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4814): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4814): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4814): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4814): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4814): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4814): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4814): Opened ClientFlag.db in read-only mode
D/Process ( 4814): killProcess, pid=4814
D/Process ( 4814): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  910): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4836 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4814
I/ActivityManager(  910): Process com.google.android.apps.docs (pid 4814) has died.
W/ContextImpl( 4836): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4836): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4836): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4836): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4836): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4836): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4836): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4836): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4836): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4836): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4836): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4836): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4836): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4836): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4836): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4836): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4836): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4836): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4836): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4836): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4836): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4836): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4836): threadid=10: thread exiting with uncaught exception (group=0x416fce30)
E/AndroidRuntime( 4836): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4836): Process: com.android.keychain, PID: 4836
E/AndroidRuntime( 4836): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4836): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4836): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4836): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4836): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4836): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4836): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4836): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4836): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4836): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4836): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4836): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4836): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4836): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4836): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4836): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4836): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4836): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4836): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4836): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  910): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4850 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  910): App crashed! Process: com.android.keychain
D/ErrorReport(  910): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4836): killProcess, pid=4836
D/Process ( 4836): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  910): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  910): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1451958676368.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  910): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  910): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  910): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  910): 	... 4 more
I/ActivityManager(  910): Recipient 4836
I/ActivityManager(  910): Process com.android.keychain (pid 4836) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10748ms
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AppTag  ( 4850): getInstance(Context context)
D/PMS     (  910): acquireWL(43fa85e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(43fa85e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/AppTag  ( 4850): getInstance(Context context)
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/AppTag  ( 4850): onCreate()
D/DotMatrix( 1584): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1584): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): acquireWL(4379cd20): PARTIAL_WAKE_LOCK  AsyncService 0x1 4144 10160 null
W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
D/PMS     (  910): releaseWL(4379cd20): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  910): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4869 uid=10098 gids={50098, 3003, 5012}
I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
I/DeviceManagement( 4869): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4869 dbg=false s=true
I/DeviceManagement( 4869): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4869): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4869): WorkflowService: Starting workflow service
I/DeviceManagement( 4869): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b5e0e0] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4869): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4869): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4869): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4869): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  910): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4883 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4869): BackgroundController: *** Processing package remove for appID=com.test.thalitest

```
