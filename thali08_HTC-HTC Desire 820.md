#### Test 56151093c886730_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 67
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
--------- beginning of /dev/log/system
D/WIFI_ICON( 1119): WifiActivity: 1
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/cutils-trace( 4363): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4363): ====startRecUseTime====
D/htc.customization.log.level( 4363):  is 
W/CustomizationLogLevel( 4363): Level value is invalid, use default level 2
D/CustomizationManager( 4363):  Read ACC file spent 0.063 (s)
D/CIDMapFileReader( 4363): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4363): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4363): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4363): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4363): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4363): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4363): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4363): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4363): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4363): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4363): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4363): Parsing tag category name = system
I/CustomizationCIDLoader( 4363): Parsing tag category name = application
I/CustomizationCIDLoader( 4363): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4363): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4363): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4363): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4363): Parsing tag category name = Settings
D/CustomizationManager( 4363):  Read CID file spent 0.105 (s)
D/CustomizationManager( 4363):  All configurations done spent 0.105 (s)
W/HtcNativeFlag( 4363): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4363): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4363): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4363): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4363
D/PMS     (  905): acquireHCC(41f71420): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(41e62680): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
W/asset   (  905): Copying FileAsset 0x69f953b8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1109357952
D/PMS     (  905): acquireWL(41ae2720): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/FeedHostManager( 1275): [onPause]
I/FeedProviderManager( 1275): onPause
I/FeedHostManager( 1275): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c763a0
I/SocialFeedProvider( 1275): +onPause
I/SocialFeedProvider( 1275): -onPause
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4374 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1275): [trimMemory] 20
W/asset   ( 4374): Copying FileAsset 0x5c741420 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4374): Binding Chromium to main looper Looper (main, tid 1) {41ac6d90}
I/LibraryLoader( 4374): Expected native library version number "",actual native library version number ""
I/chromium( 4374): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4374): Initializing chromium process, renderers=0
D/PMS     (  905): acquireWL(425686d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): acquireWL(42518308): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): releaseWL(425686d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4246e300:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4374): 1101909512: getState(). Returning 12
I/Adreno-EGL( 4374): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4374): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4374): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4374): Local Branch: 
I/Adreno-EGL( 4374): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4374): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4374):                  aa63bbd948f41d15fc72f585e
W/chromium( 4374): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4374): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4374): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4374): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4374): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4374): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4374): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4374): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4374): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/PMS     (  905): acquireWL(42346698): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
D/SystemWebViewEngine( 4374): CordovaWebView is running on device made by: HTC
D/PMS     (  905): releaseWL(42346698): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  905): acquireWL(42f39a08): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  905): releaseWL(42f39a08): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(41c1ef80): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  905): releaseWL(41c1ef80): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(44133a10): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,W/AwContents( 4374): nativeOnDraw failed; clearing to background color.
D/PMS     (  905): releaseWL(44133a10): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/InputMethodManagerService(  905): Disable input method client, pid=1275
,I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +305ms
W/ResourceType( 4374): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4374): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b0e4f8, mServedView=org.apache.cordova.engine.SystemWebView{41ad4120 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 4374): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  905): Enable input method client, pid=4374
W/XT9_C   ( 1212): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1212): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  905): releaseWL(41ae2720): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4374): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4374): JniHelper::setJavaVM(0x415a1048), pthread_self() = 1662873216
,D/JX-Cordova( 4374): jxcore cordova android initializing
,I/dalvikvm-heap( 4374): Grow heap (frag case) to 12.037MB for 63974-byte allocation
,I/dalvikvm-heap( 4374): Grow heap (frag case) to 12.094MB for 95956-byte allocation
,I/dalvikvm-heap( 4374): Grow heap (frag case) to 12.174MB for 143930-byte allocation
,I/dalvikvm-heap( 4374): Grow heap (frag case) to 12.289MB for 215890-byte allocation
,I/dalvikvm-heap( 4374): Grow heap (frag case) to 12.458MB for 323830-byte allocation
,I/dalvikvm-heap( 4374): Grow heap (frag case) to 13.115MB for 728606-byte allocation
,I/dalvikvm-heap( 4374): Grow heap (frag case) to 13.712MB for 1092904-byte allocation
,I/dalvikvm-heap( 4374): Grow heap (frag case) to 14.631MB for 1639352-byte allocation
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 86
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/dalvikvm-heap( 4374): Grow heap (frag case) to 15.939MB for 2459024-byte allocation
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4422 uid=10077 gids={50077}
,D/PMS     (  905): acquireWL(41c16100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10077}
V/AlarmManager(  905): sending alarm PendingIntent{4207e9d8: PendingIntentRecord{425a8108 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453034319488, Int=60000
,D/PMS     (  905): releaseWL(41c16100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4422): SMSBackupAgentService started
,D/SMSBackup( 4422): Checking restore status
D/SMSBackup( 4422): Restore complete
,D/SMSBackup( 4422): cancelCheckAlarm
,D/SMSBackup( 4422): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  905): killProcessQuiet, pid=3336
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3336:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3336
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
,W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(41f71420): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(41e62680): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4374): Grow heap (frag case) to 18.064MB for 3688532-byte allocation
,W/jxcore-log( 4374): Initializing JXcore engine
,W/jxcore-log( 4374): JXcore engine is ready
,W/jxcore-log( 4374): Starting JXcore engine
,W/jxcore-log( 4374): Platform android
W/jxcore-log( 4374): 
,W/jxcore-log( 4374): Process ARCH arm
W/jxcore-log( 4374): 
,D/PMS     (  905): acquireWL(4257e1f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/WifiDataStallTracker(  905): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  905): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  905): updateDataStallInfo: mDataStallTxRxSum={txSum=70 rxSum=55} preTxRxSum={txSum=69 rxSum=54}
D/WifiDataStallTracker(  905): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  905): onDataStallAlarm: tag=20359 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=20360 delay=15s
V/AlarmManager(  905): sending alarm PendingIntent{42402258: PendingIntentRecord{424e1a40 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105552, Int=0
D/PMS     (  905): releaseWL(4257e1f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): releaseWL(42518308): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4374): JXcore Cordova bridge is ready!
I/jxcore-log( 4374): 
,W/jxcore-log( 4374): JXcore engine is started
,I/chromium( 4374): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4374): Toggling radios to true
I/jxcore-log( 4374): 
,D/BluetoothAdapter( 4374): enable(): BT is already enabled..!
,D/WifiManager( 4374): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1102
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
,D/WifiManager( 4374): disconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiNative-wlan0(  905): doBoolean: DISCONNECT
D/WifiManager( 4374): reconnect: Base Package Name=com.test.thalitest, uid=10189
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): TDLS: Tear down peers
,I/wpa_supplicant( 1136): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4374): Radios toggled
I/jxcore-log( 4374): 
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: true pid=4374, uid=10189
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4374): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4374): 
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1136): Clean 'force_connect' when disconnect
,I/wpa_supplicant( 1136): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1136): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3
D/wpa_supplicant( 1136): TDLS: Remove peers on disassociation
D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1136): send_and_recv error -67 - cmd 12
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1136): send_and_recv error -67 - cmd 12
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1136): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1136): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7aecbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1136):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1136): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1136): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1136): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1136): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1136): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1136): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1136): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplican,t port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1136): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1136): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1136): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1136): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1136): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1136): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1136): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiNative-wlan0(  905):    returned true
D/WifiPerfLock(  905): release()
,D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): Power_Mode_Type mode = 0
I/wpa_supplicant( 1136): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
,D/DhcpStateMachine(  905): [RunningState] Stop DHCP
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  905): acquireWL(42418090): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  905): doBoolean: RECONNECT
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): Fast associate: Old scan results
I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): Enter handleNetworkDisconnect
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20360 mDataStallAlarmIntent=PendingIntent{42416ee8: PendingIntentRecord{424e1a40 android broadcastIntent}}
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): Power_Mode_Type mode = 0
I/wpa_supplicant( 1136): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 61
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiNative-wlan0(  905):    returned true
D/UsbnetStateTracker(  905): isAvailable+-
D/UsbnetStateTracker(  905): reconnect
,D/UsbnetStateTracker(  905): isAvailable+-
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3785): >>>>>WISPrService start isConnected = false<<<<<
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  905): Exit handleNetworkDisconnect
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WISPrService( 3785): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiService(  905): New client listening to asynchronous messages
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WISPrService( 3785): >>>>>WISPrService start isConnected = false<<<<<
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/ConnectivityService(  905): resetConnections(wlan0, 3)
D/PMS     (  905): acquireWL(425b6f90): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10028 null
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/libc    (  363): [NET] entry_id:6   entry:0xb8951138  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb8950f78  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb89552a0  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8955428  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb8951320  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb8954fd8  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb89550f8  removed 
D/libc    (  363): [NET] entry_id:8   entry:0xb89514e8  removed 
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/WISPrService( 3785): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  905): acquireWL(42312b08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  905): releaseWL(42312b08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
I//system/bin/ip(  363): RTNETLINK answers: No such process
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  905): acquireWL(43e80908): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (1366/10028)
D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
,D/WifiNative-wlan0(  905): doBoolean: SCAN
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1136): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/BatSI   (  905): WIFI scan started for: 650a0300 uid:1000
,D/WifiNative-wlan0(  905):    returned false
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
D/PMS     (  905): releaseWL(425b6f90): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1366/10028)
D/PMS     (  905): releaseWL(43e80908): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  905): bSetPropertyMultiRAB:false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1901/1000)
D/PMS     (  905): acquireWL(441a3638): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(441a3638): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10075)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3854/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4264/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,I/ConnectivityHelper( 1275): [onReceive] WIFI(1): DISCONNECTED
I/Tethering(  905): ipv4Default null
I/Tethering(  905): No IPv4 upstream interface, giving up.
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
I/NetworkMonitor( 3854): type=WIFI subType= reason=null isConnected=false
D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  905): NoActiveNetworkState
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1426/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4264/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1988/10021)
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4445 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4445): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4445): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4445): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4445): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4445): Preparing secondary program dexes.
V/DexLibLoader( 4445): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4445): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4445): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4445): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4445): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4445): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4445): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4445): Dex already copied
D/OdexVerifier( 4445): Odex verification is skipped.
,V/DexLibLoader( 4445): Creating class loader
,V/DexLibLoader( 4445): Finished creating class loader
V/DexLibLoader( 4445): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4445): Dex already copied
D/OdexVerifier( 4445): Odex verification is skipped.
,V/DexLibLoader( 4445): Creating class loader,
V/DexLibLoader( 4445): Finished creating class loader
V/DexLibLoader( 4445): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar,
V/DexLibLoader( 4445): Dex already copied
D/OdexVerifier( 4445): Odex verification is skipped.
,V/DexLibLoader( 4445): Creating class loader
,V/DexLibLoader( 4445): Finished creating class loader
V/DexLibLoader( 4445): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4445): Dex already copied
D/OdexVerifier( 4445): Odex verification is skipped.
,V/DexLibLoader( 4445): Creating class loader,
V/DexLibLoader( 4445): Finished creating class loader
,V/DexLibLoader( 4445): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4445): DexLibLoader.ensureDexLoaded took 16 ms
,W/dalvikvm( 4445): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4445): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4445): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4445): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4445): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4445): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4445): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,W/dalvikvm( 4445): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=9 entropy=0
D/wpa_supplicant( 1136): Add randomness: count=10 entropy=1
D/wpa_supplicant( 1136): Add randomness: count=11 entropy=2
D/wpa_supplicant( 1136): Add randomness: count=12 entropy=3
D/wpa_supplicant( 1136): Add randomness: count=13 entropy=4
D/wpa_supplicant( 1136): Add randomness: count=14 entropy=5
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1136): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 3
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 1
I/wpa_supplicant( 1136): wpa_s->is_screen_on 1
I/wpa_supplicant( 1136): wpa_s->i,fname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): selected network = 2
D/wpa_supplicant( 1136): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7aee4e8  current_ssid=0x0
D/wpa_supplicant( 1136): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1136): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1136): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1136): check if in concurrent case
,I/wpa_supplicant( 1136): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/wpa_supplicant( 1136): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1136): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1136): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1136): RSN: PMKSA cache search - network_ctx=0xb7aee4e8 try_opportunistic=0
D/wpa_supplicant( 1136): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1136): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1136): State: SCANNING -> ASSOCIATING,
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1136): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 1136): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1136): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1136): nl80211: Unsubscribe mgmt frames handle 0xb7aed718 (mode change)
D/wpa_supplicant( 1136): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7aed718
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb7aed718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb7aed718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb7aed718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb7aed718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb7aed718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb7aed718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb7aed718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb7aed718
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb7aed718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb7aed718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1136):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1136):   * freq=2412
D/wpa_supplicant( 1136):   * Auth Type 0
,D/wpa_supplicant( 1136):   * WPA Versions 0x2
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1136): nl80211: Connect request send successfully
D/wpa_supplicant( 1136): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1136): reply (779) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-49
I/wpa_supplicant( 1136): tsf=0000000108411682
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-57
I/wpa_supplicant( 1136): tsf=0000000108411695
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=01ABC
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-57
I/wpa_supplicant( 1136): tsf=0000000108411699
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2427
I/wpa_supplicant( 1136): level=-72
I/wpa_supplicant( 1136): tsf=0000000108411702
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-87
I/wpa_supplicant( 1136): tsf=0000000108411706
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=5
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000108411709
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC5999698
I/wpa_supplicant( 1136): ####
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING,
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 108411682, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 108411695, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 108411699, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 108411702, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 108411706, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 108411709, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 6 to mScanResults
D/BatSI   (  905): WIFI scan stopped for: 640a0300 uid:1000
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/dalvikvm( 4445): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1136): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1136): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1136): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1136): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1136): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1136): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1136): nl80211: if_removed already cleared - ignore event
E/FbInjectorInitializer( 4445): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1136): nl80211: Connect event
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1136): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1136): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1136): Add randomness: count=15 entropy=6
I/wpa_supplicant( 1136): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1136): TDLS: Remove peers on association
D/wpa_supplicant( 1136): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  905): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1136): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1136): EAPOL: enable timer tick
D/wpa_supplicant( 1136): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1136): htc_wext_set_keepalive +
I/wpa_supplicant( 1136): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1136): getPrivFuncNum +	
I/wpa_supplicant( 1136): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1136): htc_wext_set_keepalive fnum = 0x8bf6
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1136): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1136): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1136): Get randomness: len=32 entropy=7
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d,4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/WifiStateMachine(  905): Associated
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  905): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
I/wpa_supplicant( 1136): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7aed9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1136):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1136): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1136): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fb5b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1136):    broadcast key
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1136): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1136): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1136): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1136): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1136): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1136): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1136): set send_ind_to_ndc = 0
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1136): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1136): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1136): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1136): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1136): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1136): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1136): EAPOL authentication completed successfully
I/wpa_supplicant( 1136): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1136): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1136): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1136): nl80211: if_removed already cleared - ignore event
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
I/SensorManager(  905): mEventCount = 900
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 3785): >>>>>WISPrService start isConnected = false<<<<<
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/WISPrService( 3785): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/DhcpStateMachine(  905): [StoppedState] Start DHCP
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): Power_Mode_Type mode = 1
I/wpa_supplicant( 1136): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  905):    returned null
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(43a4b7f8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424a5048 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424a5048 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4445): Verify
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4445): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4445): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4445): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  905): killProcessQuiet, pid=4201
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4201:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/PMS     (  905): acquireWL(441f22b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
I/ActivityManager(  905): Recipient 4201
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,D/PMS     (  905): acquireWL(431f0558): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1226 10028 null
,D/PMS     (  905): releaseWL(441f22b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/PMS     (  905): releaseWL(431f0558): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1366): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/AutoSetting( 1454): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1454): Util - no network available!
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1454/10053)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1454/10053)
,D/AutoSetting( 1454): service - onCreate()
,D/AutoSetting( 1454): service - AddressCache: using context: com.htc.Weather
I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4474 uid=10078 gids={50078, 3003, 5012}
,D/LocationManagerService(  905): request 42497120 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 1454): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1454): service - mHandler: cancel location update
,D/AutoSetting( 1454): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4445): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4445): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4445): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4474): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4474): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4474): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4474): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4490 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4474/10078)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4474/10078)
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4474/10078)
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4445): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/dalvikvm( 4445): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4445): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/dalvikvm( 4445): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4445): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4445): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4445): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4445): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4445): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4445): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4445): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4445): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4445): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4445): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4445): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4445): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4445): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4445): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4445): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4510 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=3836
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3836:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/dalvikvm-heap( 4445): Grow heap (frag case) to 9.927MB for 39954-byte allocation
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4510): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4445): Grow heap (frag case) to 9.999MB for 79892-byte allocation
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4510): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 4510): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4510): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4510): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1136): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,I/dalvikvm-heap( 4445): Grow heap (frag case) to 10.066MB for 84664-byte allocation
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  905): releaseWL(43a4b7f8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [1][0][0]
,I/wpa_supplicant( 1136): Change stage from stage0 to stage3
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): gateway: /192.168.1.1
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1136): wlan0: Background scan every 600 seconds
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -56, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
I/dalvikvm-heap( 4445): Grow heap (frag case) to 10.093MB for 28144-byte allocation
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=20362 delay=15s
,V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  905): WAN detection
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
D/MDST    (  905): default: setEnableApn apnType =default , enable=false
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@423f78b0
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/ActivityManager(  905): Recipient 3836
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WISPrService( 3785): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  905): acquireWL(42575790): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4474/10078)
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  905): acquireWL(43216e70): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
,D/PMS     (  905): acquireWL(4332eb60): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1226 10028 null
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
D/PMS     (  905): releaseWL(43216e70): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4510/10151)
,V/WebViewChromiumFactoryProvider( 4510): Binding Chromium to main looper Looper (main, tid 1) {41acc080}
,I/LibraryLoader( 4510): Expected native library version number "",actual native library version number ""
I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/chromium( 4510): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/BrowserStartupController( 4510): Initializing chromium process, renderers=0
,I/CheckinService( 1226): Preparing to send checkin request
,I/EventLogService( 1226): Accumulating logs since 1453034268708
,D/PMS     (  905): acquireWL(43e53b48): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  905): acquireWL(44154330): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  905): releaseWL(44154330): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,E/AudioManagerAndroid( 4510): BLUETOOTH permission is missing!
D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/GoogleHttpClient( 1226): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1226): Using GMS GoogleHttpClient
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,I/Adreno-EGL( 4510): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4510): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4510): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4510): Local Branch: 
I/Adreno-EGL( 4510): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4510): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4510):                  aa63bbd948f41d15fc72f585e
D/PMS     (  905): releaseWL(42575790): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1226/10028)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (1226/10028)
,I/dalvikvm-heap( 4445): Grow heap (frag case) to 10.280MB for 75760-byte allocation
,I/NSApplication( 4510): Starting up...
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4510/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4510/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/wpa_supplicant( 1136): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1136): EAPOL: disable timer tick
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{441afcf0 u0 ReceiverList{441dbbe0 4445 com.facebook.katana/10026/u0 remote:42ce6d60}}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{441afcf0 u0 ReceiverList{441dbbe0 4445 com.facebook.katana/10026/u0 remote:42ce6d60}}
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/Process (  905): killProcessQuiet, pid=3965
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43decef0 u0 ReceiverList{441b94f0 4445 com.facebook.katana/10026/u0 remote:43d7c400}}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4113/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4113/10160)
,I/ActivityManager(  905): Killing 3965:com.google.android.gm/u0a107 (adj 15): empty #17
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,W/GLSUser ( 1366): GoogleAccountDataService.getToken()
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GCM     ( 1366): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  905): Recipient 3965
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1366): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PMS     (  905): acquireWL(43d35768): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1426 10028 null
,D/PMS     (  905): releaseWL(43d35768): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/DotMatrix( 1605): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/CheckinRequestBuilder( 1226): awaiting user notification for token
I/RemoteViews( 1119): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41bf2060 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.google.android.gms 2 8 4 12
,I/jxcore-log( 4374): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4374): 
,D/GCoreFlp( 1426): Unknown pending intent to remove.
D/PMS     (  905): acquireWL(43701ba8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1426 10028 null
D/PMS     (  905): releaseWL(43701ba8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4585 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4585): install
,I/MultiDex( 4585): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4585): loading existing secondary dex files
,I/MultiDex( 4585): load found 1 secondary dex files
,I/MultiDex( 4585): install done
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4445): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
I/ProviderInstaller( 4585): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4445): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/GCM     ( 1366): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/Settings( 4585): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4585): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4585): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4585): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4585): Local Branch: 
I/Adreno-EGL( 4585): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4585): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4585):                  aa63bbd948f41d15fc72f585e
,I/jxcore-log( 4374): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4374): 
,I/jxcore-log( 4374): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4374): 
,I/jxcore-log( 4374): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4374): 
,D/PMS     (  905): releaseWL(42418090): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  905): NetTransition Wakelock for ConnectedState released by timeout
,D/WIFI_ICON( 1119): WifiActivity: 3
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/jxcore-log( 4374): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4374): 
,I/jxcore-log( 4374): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4374): 
,I/jxcore-log( 4374): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4374): 
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,D/CaptivePortalTracker(  905): NoActiveNetworkState
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/NetworkMonitor( 3854): type=WIFI subType= reason=null isConnected=true
,V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3854/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4474/10078)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10075)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4264/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1901/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3878/10051)
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): Found interface wlan0
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
I/acms    ( 1901): Checking Certificates
I/acms    ( 1901): Checking Developer Certificates
I/acms    ( 1901): Checking Application Certificates
I/acms    ( 1901): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1901): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1901): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1901): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1901): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1901): Updating next query delay: 75600000
I/mlserverapp( 1901): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1901): cancelACMSProgrammedChecks
W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1426/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000),
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1426/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (4264/10100)
,I/ConnectivityHelper( 1275): [onReceive] WIFI(1): CONNECTED
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(42381540): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1988/10021)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42263558): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(424ee4c0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 905 1000 WorkSource{10106}
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  905): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4608 uid=10106 gids={50106, 3003, 5012}
,D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(42263558): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  905): releaseWL(42381540): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/PMS     (  905): acquireWL(42339210): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
,D/PMS     (  905): releaseWL(42339210): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1366): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1366/10028)
D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1366): [NET] getaddrinfo-,err=8
D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1366): [NET] getaddrinfo-, 1
,D/libc    ( 1366): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d25e +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1366/10028)
D/PMS     (  905): acquireWL(41cc2618): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1366 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/AutoSetting( 1454): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4474): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4474): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1454/10053)
D/AutoSetting( 1454): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1454): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1454): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1454): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1454): service - handleMessage() setting current location null
D/AutoSetting( 1454): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1454): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1454/10053)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4510/10151)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4113/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (4113/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1848/10178)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 288
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1366): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1366): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1366/10028)
D/PMS     (  905): acquireWL(42517560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
,D/PMS     (  905): releaseWL(42517560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
I/NewsWeather( 4608): LocationClient connecting
,I/NewsWeather( 4608): NewsAccounts: 2, AllSystemAccounts 1.
,E/dalvikvm( 4608): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4608): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4608): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4608): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4608): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4585/10028)
,I/Adreno-EGL( 4585): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4585): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4585): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4585): Local Branch: 
I/Adreno-EGL( 4585): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4585): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4585):                  aa63bbd948f41d15fc72f585e
,D/GCM     ( 1366): Connected
D/PMS     (  905): acquireWL(42f0a770): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1366/10028)
,I/ProviderInstaller( 4608): Installed default security provider GmsCore_OpenSSL
D/PMS     (  905): releaseWL(41cc2618): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1366/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1366/10028)
D/PMS     (  905): releaseWL(42f0a770): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): acquireWL(424c9808): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10028 null,
,I/Adreno-EGL( 4585): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4585): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4585): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4585): Local Branch: 
I/Adreno-EGL( 4585): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4585): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4585):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43d72c48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43d72c48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4608): Last usage 0, idle 1453034325s, sync interval 2592000s
,I/NewsWeather( 4608): setPeriodicSync in seconds 2592000
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1366/10028)
,I/NewsWeather( 4608): onConnected null
,D/GCM     ( 1366): Message class mpf
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1366/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1366/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1366/10028)
,W/GCoreFlp( 1426): No location to return for getLastLocation()
,I/NewsWeather( 4608): LocationClient onConnected: location null
D/PMS     (  905): acquireWL(424708d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
D/PMS     (  905): releaseWL(424c9808): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): releaseWL(424708d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  905): acquireWL(4260f700): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1426 10028 null
D/PMS     (  905): acquireWL(42edec58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1426 10028 null
D/PMS     (  905): releaseWL(4260f700): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  905): releaseWL(42edec58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4608): Skip sync for lookup editions
,I/NewsWeather( 4608): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4608): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1366): GoogleAccountDataService.getToken()
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1366): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/CheckinTask( 1226): Sending checkin request (8966 bytes)
,D/DotMatrix( 1605): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1226): [NET] getaddrinfo-, 1
,D/libc    ( 1226): [NET] getaddrinfo_proxy+
D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1119): com.google.android.gms (false,0)
,D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =259b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41c0f470 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/NewsWeather( 4608): Unrecoverable authentication exception
E/NewsWeather( 4608): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4608): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4608): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4608): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/RemoteViews.Performance( 1119): com.google.android.gms 1 6 3 12
D/libc    ( 4608): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4608): [NET] getaddrinfo-,err=8
D/libc    ( 4608): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4608): [NET] getaddrinfo-, 1
D/libc    ( 4608): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =9a48 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,I/PMS     (  905): Going to sleep due to screen timeout...
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4210bb70
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  905): pid=905, uid=1000
,W/SensorService(  905): Active sensors: size = 2
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,W/BatSI   (  905): Couldn't get kernel wake lock stats
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4210bb70, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4213aec8
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@420b6750
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/PMS     (  905): mWirelessDisplayManager is null
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 254
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1226): [NET] getaddrinfo_proxy-, success
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=70
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4608): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
,I/jxcore-log( 4374): Test app app.js loaded
I/jxcore-log( 4374): 
,I/Choreographer( 4374): Skipped 286 frames!  The application may be doing too much work on its main thread.
,D/libc    ( 4608): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4608): [NET] getaddrinfo-,err=8
,I/chromium( 4374): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/PMS     (  905): acquireWL(42b0cbe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
,E/NewsWeather( 4608): Failed to syncNewsAppData
,E/NewsWeather( 4608): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  905): releaseWL(42b0cbe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(431e3890): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 67865, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  905): releaseWL(424ee4c0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/Process (  905): killProcessQuiet, pid=4234
,I/ActivityManager(  905): Killing 4234:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1426/10028)
D/PMS     (  905): releaseWL(431e3890): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43359990): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  905): Recipient 4234
D/PMS     (  905): releaseWL(43359990): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=12 [31][4][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 375ms
D/PMS     (  905): nativeSetInteractive:false
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
,I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
D/NfcService( 1259): ScreenObserver: OFF
,D/NfcService( 1259): applyRouting - 0
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43c5f8b0)
,D/NfcService( 1259): applyRouting -2
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
D/PMN     (  905): wakingUp
D/PMS     (  905): acquireWL(43e07c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/InputMethodManagerService(  905): Disable input method client, pid=4374
D/PMS     (  905): acquireWL(441e3de8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(441e3de8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
,I/IntentController( 1119): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/WindowManager(  905): No lock screen! windowToken=null
D/PMS     (  905): releaseWL(43e07c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  905): onScreenOn
W/ResourceType( 4374): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4374): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41ad4120 VFEDH.C. .F...... 0,0-720,1134 #64}
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/MtpService( 1988): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1259): applyRouting - 0
,D/MtpService( 1988): [MTP][onReceive]-
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,D/NfcService( 1259): applyRouting -2
,D/AutoSetting( 1454): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1454): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  905): acquireWL(4419f5e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
D/PMS     (  905): releaseWL(4419f5e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/PMS     (  905): acquireWL(43340ea0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  905): releaseWL(43340ea0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/TetherSettings( 3785): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3785): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3785): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3785): Cust_ConnectToPC   : spcsc>false
D/        ( 3785): Cust_ConnectToPC   : IPT>true
D/        ( 3785): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3785): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3785): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3785): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3785): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=20363 delay=15s
,I/PSReceiver( 3785): onReceive:android.intent.action.USER_PRESENT
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,W/ContextImpl( 3785): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3785): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
W/Settings( 3785): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3785):  defaultType:0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): SET_SCREEN_ON:On,
I/wpa_supplicant( 1136): htc_wext_set_keepalive +
I/wpa_supplicant( 1136): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1136): getPrivFuncNum +	
I/wpa_supplicant( 1136): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1136): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1136): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1136): BG scan when screen On
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): Match BG scan, scan!
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
D/WifiNative-wlan0(  905):    returned true
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/ClockThread( 1119): stop update clock
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  905): updateScreenOn: false
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1226/10028)
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (1226/10028)
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4651 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1806): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1806): onScreenOn: 1453034326313
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1806): onScreenOn: 1453034326313
D/PMS     (  905): acquireWL(43c5fbf8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1426 10028 null
D/PMS     (  905): releaseWL(43c5fbf8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4213aec8
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4213aec8, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@420b6750
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  905): goingToSleep
,W/GLSUser ( 1366): GoogleAccountDataService.getToken()
W/ContextImpl( 4651): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  905): acquireWL(42ed1330): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42ed1330): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/PMS     (  905): acquireWL(435017e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4651 1000 null
,D/SmartSyncUtils( 4651): isEpsOn(), nState = 0
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20363 mDataStallAlarmIntent=PendingIntent{42ebace8: PendingIntentRecord{424e1a40 android broadcastIntent}}
W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1366): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PMS     (  905): acquireWL(435677f8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
D/PMS     (  905): releaseWL(435017e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4651): getMobilePolicyEnabled, result = true
,D/Process (  905): killProcessQuiet, pid=4264
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): SET_SCREEN_ON:Off
I/wpa_supplicant( 1136): htc_wext_set_keepalive +
I/wpa_supplicant( 1136): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1136): getPrivFuncNum +	
I/wpa_supplicant( 1136): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1136): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1136): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1136): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1136): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905):    returned true
,I/ActivityManager(  905): Killing 4264:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/WifiStateMachine(  905): BroadcastRSSIForIMS, newrssi =-57 , oldRssi= -200
W/CheckinRequestBuilder( 1226): awaiting user notification for token
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0,
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/DotMatrix( 1605): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,I/RemoteViews( 1119): com.google.android.gms (false,0)
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 4651): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41e68ab0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/SmartSyncUtils( 4651): isEpsOn(), nState = 0
D/SmartSyncUtils( 4651): getMobilePolicyEnabled, result = true
I/RemoteViews.Performance( 1119): com.google.android.gms 1 10 3 12
I/CheckinTask( 1226): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
W/GoogleHttpClient( 1226): Unable to close GMS GoogleHttpClient
D/SmartSyncUtils( 4651): isEpsOn(), nState = 0
,D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
D/WifiService(  905): New client listening to asynchronous messages
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
D/PMS     (  905): releaseWL(435677f8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/NetworkPolicy(  905): updateScreenOn: false
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/ContactMessageStore( 1248): start background delete task...
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/ContactMessageStore( 1248): size: 0 , 0
,D/ContactMessageStore( 1248): Background delete complete
I/ActivityManager(  905): Recipient 4264
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@420b6750
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
,W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@420b6750, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@420b6750, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@420b6750
,D/GCM     ( 1366): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4244c9b8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4244c9b8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/PMS     (  905): releaseWL(4332eb60): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1226): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41cbaf60 that was originally bound here
E/ActivityThread( 1226): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41cbaf60 that was originally bound here
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
E/ActivityThread( 1226): 	at java.util.concurrent.FutureTask.run(FutureTa,sk.java:237)
E/ActivityThread( 1226): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1366): GCM config loaded
,D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] getTotalRam: 1873 Mb
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1806): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1806): onScreenOff
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1806): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1806): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1806): onScreenOff
D/PMS     (  905): acquireWL(43db0d50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1426 10028 null
,D/PMS     (  905): releaseWL(43db0d50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/AutoSetting( 1454): service - mHandler: cancel location update
D/AutoSetting( 1454): service -           changes count: 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,W/fb4a(:<default>):UserScope( 4445): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4445): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4445): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4445/10026)
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4662 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/PMS     (  905): releaseWL(43e53b48): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/104.81.130.175
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/AutoSetting( 1522): service - handleMessage() stop self
,D/AutoSetting( 1522): service - onDestroy() END
,D/AutoSetting( 1522): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4280
,I/ActivityManager(  905): Killing 4280:com.htc.backup/1000 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 4280
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV2    ( 4510): Thread[GAThread,5,main]: No campaign data found.
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-76
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=16 entropy=0
D/wpa_supplicant( 1136): Add randomness: count=17 entropy=1
D/wpa_supplicant( 1136): Add randomness: count=18 entropy=2
D/wpa_supplicant( 1136): Add randomness: count=19 entropy=3
D/wpa_supplicant( 1136): Add randomness: count=20 entropy=4
D/wpa_supplicant( 1136): Add randomness: count=21 entropy=5
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1136): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplica,nt( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-76
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-87
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=22 entropy=6
D/wpa_supplicant( 1136): Add randomness: count=23 entropy=7
D/wpa_supplicant( 1136): Add randomness: count=24 entropy=8
D/wpa_supplicant( 1136): Add randomness: count=25 entropy=9
D/wpa_supplicant( 1136): Add randomness: count=26 entropy=10
D/wpa_supplicant( 1136): Add randomness: count=27 entropy=11
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP 64:7c:34:12:7f:81 type 0 added
,D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
,W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: DISCONNECTED -> INACTIVE
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1136): reply (779) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-49
I/wpa_supplicant( 1136): tsf=0000000114311825
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-57
I/wpa_supplicant( 1136): tsf=0000000114311851
,I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=01ABC
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-57
I/wpa_supplicant( 1136): tsf=0000000114311862
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2427
I/wpa_supplicant( 1136): level=-76
I/wpa_supplicant( 1136): tsf=0000000114311872
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-87,
I/wpa_supplicant( 1136): tsf=0000000114311881
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=5
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000114311891
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS],
I/wpa_supplicant( 1136): ssid=UPC5999698
I/wpa_supplicant( 1136): ####
D/WifiP2pService(  905): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): InactiveState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@41c3f0a0 target=com.android.internal.util.StateMachine$SmHandler },
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  905): P2pEnabledState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@41c3f0a0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): DefaultState{ when=-5ms what=147462 obj=android.net.wifi.StateChangeResult@41c3f0a0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 114311825, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 114311851, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 114311862, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2427, timestamp: 114311872, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2437, timestamp: 114311881, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 114311891, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 6 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  74, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  7 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  74, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  7 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList,
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/GAV4    ( 4608): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  905): killProcessQuiet, pid=4304
,I/ActivityManager(  905): Killing 4304:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4304
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{4365a3f8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(42502cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{423080f8: PendingIntentRecord{4232e228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=125134, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42502cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(41ef72c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41cef980: PendingIntentRecord{4246a148 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=128650, Int=0
,D/PMS     (  905): acquireWL(42ec66d0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): releaseWL(41ef72c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(424a88a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42ec66d0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(424a88a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-76
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
D/wpa_supplicant( 1136): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=28 entropy=12
D/wpa_supplicant( 1136): Add randomness: count=29 entropy=13
D/wpa_supplicant( 1136): Add randomness: count=30 entropy=14
D/wpa_supplicant( 1136): Add randomness: count=31 entropy=15
D/wpa_supplicant( 1136): Add randomness: count=32 entropy=16
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1136): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136):, Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-76
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
D/wpa_supplicant( 1136): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=33 entropy=17
D/wpa_supplicant( 1136): Add randomness: count=34 entropy=18
D/wpa_supplicant( 1136): Add randomness: count=35 entropy=19
D/wpa_supplicant( 1136): Add randomness: count=36 entropy=20
D/wpa_supplicant( 1136): Add randomness: count=37 entropy=21
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+,
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1136): reply (779) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-49
I/wpa_supplicant( 1136): tsf=0000000131684150
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-57
I/wpa_supplicant( 1136): tsf=0000000131684179
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=01ABC
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-57
I/wpa_supplicant( 1136): tsf=0000000131684189
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2427
I/wpa_supplicant( 1136): level=-76
I/wpa_supplicant( 1136): tsf=0000000131684199
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000131684208
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=5
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000114311891
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC5999698
I/wpa_supplicant( 1136): ####
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 131684150, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 131684179, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 131684189, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2427, timestamp: 131684199, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 131684208, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 114311891, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 6 to mScanResults
V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  74, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  7 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  74, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  7 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/PMS     (  905): acquireWL(431dc438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
,D/PMS     (  905): releaseWL(431dc438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1454): service - mHandler: update timezone
,D/AutoSetting( 1522): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1522): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1522): service - onCreate()
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1522): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1522): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1605): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1522): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1522): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1522): service - mHandler: update timezone
,D/AutoSetting( 1522): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1522): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1522): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1522): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1605): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41b13d88 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 3 7 2 11
,D/AutoSetting( 1454): service - handleMessage() stop self
,D/AutoSetting( 1454): service - handleMessage() quit looper
,D/AutoSetting( 1454): service - onDestroy() END
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  905): killProcessQuiet, pid=3878
,I/ActivityManager(  905): Killing 3878:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 3878
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-89
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=38 entropy=22
D/wpa_supplicant( 1136): Add randomness: count=39 entropy=23
D/wpa_supplicant( 1136): Add randomness: count=40 entropy=24
D/wpa_supplicant( 1136): Add randomness: count=41 entropy=25
D/wpa_supplicant( 1136): Add randomness: count=42 entropy=26
D/wpa_supplicant( 1136): Add randomness: count=43 entropy=27
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rs,n_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 4: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 5: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-89
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=44 entropy=28
D/wpa_supplicant( 1136): Add randomness: count=45 entropy=29
D/wpa_supplicant( 1136): Add randomness: count=46 entropy=30
D/wpa_supplicant( 1136): Add randomness: count=47 entropy=31
D/wpa_supplicant( 1136): Add randomness: count=48 entropy=32
D/wpa_supplicant( 1136): Add randomness: count=49 entropy=33
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1136): Recv C,md 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1136): reply (907) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-49
I/wpa_supplicant( 1136): tsf=0000000149113027
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-57
I/wpa_supplicant( 1136): tsf=0000000131684179
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=01ABC
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-57
I/wpa_supplicant( 1136): tsf=0000000149113049
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2427
I/wpa_supplicant( 1136): level=-77
I/wpa_supplicant( 1136): tsf=0000000149113059
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000149113068
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=6
I/wpa_supplicant( 1136): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000149113077
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=7
I/wpa_supplicant( 1136): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-89
I/wpa_supplicant( 1136): tsf=0000000149113088
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC243894600
I/wpa_supplicant( 1136): ####
D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android,.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 149113027, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 131684179, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 149113049, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 149113059, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 149113068, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2437, timestamp: 149113077, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2437, timestamp: 149113088, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 7 to mScanResults
V/ScoreHelper(  905): Only print Top 10 in ApScanList
D/WirelessDisplayService(  905): getDiscoveryDongleList
V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  72, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  72, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  72, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  4 [-89], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (7) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{435976a8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  905): acquireWL(424e40a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10028}
,V/AlarmManager(  905): sending alarm PendingIntent{44100480: PendingIntentRecord{424c1870 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141657, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{42395cb8: PendingIntentRecord{4234a0c8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141936, Int=0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1366/10028)
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
V/AlarmManager(  905): sending alarm PendingIntent{41cef980: PendingIntentRecord{4246a148 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=158672, Int=0
D/PMS     (  905): acquireWL(42eaa7d0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(43e77020): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
D/PMS     (  905): acquireWL(42c82d80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4325c918): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(424e40a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): releaseWL(42c82d80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=8 [24][2][0]
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =803c +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [1][0][0],
,D/PMS     (  905): acquireWL(4358edd8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 905 1000 WorkSource{10106}
,D/PMS     (  905): releaseWL(43e77020): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(4325c918): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4261a300): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,I/NewsWeather( 4608): Last usage 0, idle 1453034373s, sync interval 2592000s
,I/NewsWeather( 4608): setPeriodicSync in seconds 2592000
,D/PMS     (  905): releaseWL(4261a300): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,I/NewsWeather( 4608): Skip sync for lookup editions
,I/NewsWeather( 4608): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4608): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,W/GLSUser ( 1366): GoogleAccountDataService.getToken()
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1366): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1605): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1119): com.google.android.gms (false,0)
,E/NewsWeather( 4608): Unrecoverable authentication exception
E/NewsWeather( 4608): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4608): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4608): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4608): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41bf2060 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.google.android.gms 4 10 3 12
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  905): acquireWL(42383a70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
E/NewsWeather( 4608): Failed to syncNewsAppData
,E/NewsWeather( 4608): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  905): releaseWL(42383a70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(431e7148): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4358edd8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
D/SyncManager(  905): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 111100, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1426/10028)
D/PMS     (  905): releaseWL(431e7148): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42591580): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42591580): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
,D/PMS     (  905): releaseWL(42eaa7d0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
I/wpa_supplicant( 1136): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-89
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=50 entropy=34
D/wpa_supplicant( 1136): Add randomness: count=51 entropy=35
D/wpa_supplicant( 1136): Add randomness: count=52 entropy=36
D/wpa_supplicant( 1136): Add randomness: count=53 entropy=37
D/wpa_supplicant( 1136): Add randomness: count=54 entropy=38
D/wpa_supplicant( 1136): Add randomness: count=55 entropy=39
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 3: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_,len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 5: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
I/wpa_supplicant( 1136): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-89
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=56 entropy=40
D/wpa_supplicant( 1136): Add randomness: count=57 entropy=41
D/wpa_supplicant( 1136): Add randomness: count=58 entropy=42
D/wpa_supplicant( 1136): Add randomness: count=59 entropy=43
D/wpa_supplicant( 1136): Add randomness: count=60 entropy=44
D/wpa_supplicant( 1136): Add randomness: count=61 entropy=45
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1136): reply (794) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-48
I/wpa_supplicant( 1136): tsf=0000000166433894
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-57
I/wpa_supplicant( 1136): tsf=0000000166433920
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2427
I/wpa_supplicant( 1136): level=-78
I/wpa_supplicant( 1136): tsf=0000000149113059
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000166433941
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=6
I/wpa_supplicant( 1136): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-87
I/wpa_supplicant( 1136): tsf=0000000166433961
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=7
I/wpa_supplicant( 1136): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-89
I/wpa_supplicant( 1136): tsf=0000000166433951
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC243894600
I/wpa_supplicant( 1136): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 166433894, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 166433920, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2427, timestamp: 149113059, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 166433941, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2437, timestamp: 166433961, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2437, timestamp: 166433951, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 6 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  72, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  72, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-87], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  72, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  4 [-89], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1,
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1522): service - handleMessage() stop self
,D/AutoSetting( 1522): service - onDestroy() END
,D/AutoSetting( 1522): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4322
,I/ActivityManager(  905): Killing 4322:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 4322
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(43aaf0c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(43aaf0c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1248): switchBindHtcMsgCursor: null
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
I/wpa_supplicant( 1136): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-89
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1136): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=62 entropy=46
D/wpa_supplicant( 1136): Add randomness: count=63 entropy=47
D/wpa_supplicant( 1136): Add randomness: count=64 entropy=48
D/wpa_supplicant( 1136): Add randomness: count=65 entropy=49
D/wpa_supplicant( 1136): Add randomness: count=66 entropy=50
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 3: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
D/wpa_supplicant( 1136): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD, CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
I/wpa_supplicant( 1136): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-89
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1136): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=67 entropy=51
D/wpa_supplicant( 1136): Add randomness: count=68 entropy=52
D/wpa_supplicant( 1136): Add randomness: count=69 entropy=53
D/wpa_supplicant( 1136): Add randomness: count=70 entropy=54
D/wpa_supplicant( 1136): Add randomness: count=71 entropy=55
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1136): reply (941) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-48
I/wpa_supplicant( 1136): tsf=0000000183774396
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-57
I/wpa_supplicant( 1136): tsf=0000000183774424
,I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2427
I/wpa_supplicant( 1136): level=-78
I/wpa_supplicant( 1136): tsf=0000000183774437
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000166433941
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=6
I/wpa_supplicant( 1136): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-87
I/wpa_supplicant( 1136): tsf=0000000166433961
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=7
I/wpa_supplicant( 1136): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-89
I/wpa_supplicant( 1136): tsf=0000000183774447
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC243894600
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=8
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-90
I/wpa_supplicant( 1136): tsf=0000000183774458
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC5999698
I/wpa_supplicant( 1136): ####
,D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 183774396, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 183774424, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2427, timestamp: 183774437, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 166433941, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  905): 4: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2437, timestamp: 166433961, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2437, timestamp: 183774447, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 183774458, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 7 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  70, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  70, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-87], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  70, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  4 [-89], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  66, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (7) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(437e1118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{423080f8: PendingIntentRecord{4232e228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=185134, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(437e1118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(434f9e78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41cef980: PendingIntentRecord{4246a148 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=188748, Int=0
,D/PMS     (  905): acquireWL(4414be68): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): releaseWL(434f9e78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(425807a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4414be68): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(425807a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(435d79d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(435d79d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1136): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-86
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1136): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=72 entropy=56
D/wpa_supplicant( 1136): Add randomness: count=73 entropy=57
D/wpa_supplicant( 1136): Add randomness: count=74 entropy=58
D/wpa_supplicant( 1136): Add randomness: count=75 entropy=59
D/wpa_supplicant( 1136): Add randomness: count=76 entropy=60
D/wpa_supplicant( 1136): Add randomness: count=77 entropy=61
D/wpa_supplicant( 1136): Add randomness: count=78 entropy=62
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 3: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 ,series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 6: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1136): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-86
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1136): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=79 entropy=63
D/wpa_supplicant( 1136): Add randomness: count=80 entropy=64
D/wpa_supplicant( 1136): Add randomness: count=81 entropy=65
D/wpa_supplicant( 1136): Add randomness: count=82 entropy=66
D/wpa_supplicant( 1136): Add randomness: count=83 entropy=67
D/wpa_supplicant( 1136): Add randomness: count=84 entropy=68
D/wpa_supplicant( 1136): Add randomness: count=85 entropy=69
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1136): reply (1054) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-48
,I/wpa_supplicant( 1136): tsf=0000000201124472
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-57
I/wpa_supplicant( 1136): tsf=0000000201124498
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2427
I/wpa_supplicant( 1136): level=-77
I/wpa_supplicant( 1136): tsf=0000000201124509
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000201124530
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=6
I/wpa_supplicant( 1136): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-86
I/wpa_supplicant( 1136): tsf=0000000201124540
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1136): ====
,I/wpa_supplicant( 1136): id=7
I/wpa_supplicant( 1136): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-89
I/wpa_supplicant( 1136): tsf=0000000183774447
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC243894600
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=8
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-90
I/wpa_supplicant( 1136): tsf=0000000201124519
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC5999698
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=9
I/wpa_supplicant( 1136): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=000
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 201124472, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 201124498, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 201124509, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 201124530, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -86, frequency: 2437, timestamp: 201124540, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2437, timestamp: 183774447, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 201124519, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 7: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -91, frequency: 2412, timestamp: 201124553, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 8 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-91], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  70, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  70, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-86], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  70, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  4 [-89], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  66, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (8) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1136): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=86 entropy=70
D/wpa_supplicant( 1136): Add randomness: count=87 entropy=71
D/wpa_supplicant( 1136): Add randomness: count=88 entropy=72
D/wpa_supplicant( 1136): Add randomness: count=89 entropy=73
D/wpa_supplicant( 1136): Add randomness: count=90 entropy=74
D/wpa_supplicant( 1136): Add randomness: count=91 entropy=75
D/wpa_supplicant( 1136): Add randomness: count=92 entropy=76
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26, rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 4: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 6: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-90
I/wpa_supplicant( 1136): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=93 entropy=77
D/wpa_supplicant( 1136): Add randomness: count=94 entropy=78
D/wpa_supplicant( 1136): Add randomness: count=95 entropy=79
D/wpa_supplicant( 1136): Add randomness: count=96 entropy=80
D/wpa_supplicant( 1136): Add randomness: count=97 entropy=81
D/wpa_supplicant( 1136): Add randomness: count=98 entropy=82
D/wpa_supplicant( 1136): Add randomness: count=99 entropy=83
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_D,ONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1136): reply (924) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-48
I/wpa_supplicant( 1136): tsf=0000000218525658
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-57
I/wpa_supplicant( 1136): tsf=0000000218525684
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2427
I/wpa_supplicant( 1136): level=-77
I/wpa_supplicant( 1136): tsf=0000000218525695
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000218525714
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=6
I/wpa_supplicant( 1136): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000218525724
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=8
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-90
I/wpa_supplicant( 1136): tsf=0000000218525704
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC5999698
I/wpa_supplicant( 1136): ====
I/wpa_suppli,cant( 1136): id=9
I/wpa_supplicant( 1136): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000218525734
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=WDA83
I/wpa_supplicant( 1136): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 218525658, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 218525684, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 218525695, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 218525714, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2437, timestamp: 218525724, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 218525704, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -91, frequency: 2412, timestamp: 218525734, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 7 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  72, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  72, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-91], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  68, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (7) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43da0540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41cef980: PendingIntentRecord{4246a148 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=220800, Int=0
,D/PMS     (  905): acquireWL(441dfad8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
D/PMS     (  905): releaseWL(43da0540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(44180948): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=1 [56][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(441ade00): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 905 1000 WorkSource{10106}
,D/PMS     (  905): releaseWL(441dfad8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(44180948): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43d96c90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,I/NewsWeather( 4608): Last usage 0, idle 1453034435s, sync interval 2592000s
,I/NewsWeather( 4608): setPeriodicSync in seconds 2592000
D/PMS     (  905): releaseWL(43d96c90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4608): Skip sync for lookup editions
,I/NewsWeather( 4608): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4608): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1366): GoogleAccountDataService.getToken()
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1366): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1605): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1119): com.google.android.gms (false,0)
,E/NewsWeather( 4608): Unrecoverable authentication exception
E/NewsWeather( 4608): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4608): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4608): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4608): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4608): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41da9e78 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.google.android.gms 1 11 3 12
,D/PMS     (  905): acquireWL(42f68178): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
,D/PMS     (  905): releaseWL(42f68178): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
E/NewsWeather( 4608): Failed to syncNewsAppData
,E/NewsWeather( 4608): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42a750e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 159082, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  905): releaseWL(441ade00): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1426/10028)
,D/PMS     (  905): releaseWL(42a750e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PMS     (  905): acquireWL(43d41328): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(43d41328): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
,D/PMS     (  905): acquireWL(43df9780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{4204c9f0: PendingIntentRecord{42b34838 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229579, Int=0
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4697 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{42575ef8: PendingIntentRecord{425c9498 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453034435509, Int=10800000
,D/PMS     (  905): releaseWL(43df9780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4697/10047)
,D/Process (  905): killProcessQuiet, pid=4251
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4251:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4251
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/PMS     (  905): acquireWL(428d3d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10026}
,V/AlarmManager(  905): sending alarm PendingIntent{435aaa80: PendingIntentRecord{42cc5208 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=231307, Int=120000
,V/AlarmManager(  905): sending alarm PendingIntent{43d3fe20: PendingIntentRecord{42b34838 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231480, Int=0
,D/PMS     (  905): releaseWL(428d3d68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026},
,D/PMS     (  905): acquireWL(43d72ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): releaseWL(43d72ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
W/ContextImpl( 4651): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3785): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3785): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3785): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3785): Cust_ConnectToPC   : spcsc>false
D/        ( 3785): Cust_ConnectToPC   : IPT>true
,D/        ( 3785): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3785): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3785): Index of the first 1 = -1
W/Settings( 3785): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3785): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3785): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3785): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3785): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,W/ContextImpl( 3785): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 3785): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-91
I/wpa_supplicant( 1136): [NULL] 80:f5:03:a6:74:13 freq=2462 level=-91
I/wpa_supplicant( 1136): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-92
D/wpa_supplicant( 1136): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=100 entropy=84
D/wpa_supplicant( 1136): Add randomness: count=101 entropy=85
D/wpa_supplicant( 1136): Add randomness: count=102 entropy=86
D/wpa_supplicant( 1136): Add randomness: count=103 entropy=87
D/wpa_supplicant( 1136): Add randomness: count=104 entropy=88
D/wpa_supplicant( 1136): Add randomness: count=105 entropy=89
D/wpa_supplicant( 1136): Add randomness: count=106 entropy=90
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP 80:f5:03:a6:74:13 type 0 added
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP 0c:bd:51:2b:c1:25 type 0 added
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[5] 80:f5:03:a6:74:13 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[6] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): ,End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 4: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 5: 80:f5:03:a6:74:13 ssid='UPC246351350' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
D/wpa_supplicant( 1136): 6: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-91
I/wpa_supplicant( 1136): [NULL] 80:f5:03:a6:74:13 freq=2462 level=-91
I/wpa_supplicant( 1136): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-92
D/wpa_supplicant( 1136): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=107 entropy=91
D/wpa_supplicant( 1136): Add randomness: count=108 entropy=92
D/wpa_supplicant( 1136): Add randomness: count=109 entropy=93
D/wpa_supplicant( 1136): Add randomness: count=110 entropy=94
D/wpa_supplicant( 1136): Add randomness: count=111 entropy=95
D/wpa_supplicant( 1136): Add randomness: count=112 entropy=96
D/wpa_supplicant( 1136): Add randomness: count=113 entropy=97
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP 80:f5:03:a6:74:13 type 0 added
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP 0c:bd:51:2b:c1:25 type 0 added
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[5] 80:f5:03:a6:74:13 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[6] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES,
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1136): reply (1185) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-48
I/wpa_supplicant( 1136): tsf=0000000235924270
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-57
I/wpa_supplicant( 1136): tsf=0000000235924296
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2427
I/wpa_supplicant( 1136): level=-77
I/wpa_supplicant( 1136): tsf=0000000235924307
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4,
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000235924317
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=6
I/wpa_supplicant( 1136): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000218525724
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=8
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-90
I/wpa_supplicant( 1136): tsf=0000000218525704
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC5999698,
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=9
I/wpa_supplicant( 1136): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000235924327
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=WDA83
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=10
I/wpa_supplicant( 1136): bssid=80:f5:03:a6:74:13
I/wpa_supplicant( 1136): freq=2462
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000235924337
I/wpa_supplicant( 1136): fl
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 235924270, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 235924296, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 235924307, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 235924317, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2437, timestamp: 218525724, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  905): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 218525704, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -91, frequency: 2412, timestamp: 235924327, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 7: scan result = SSID: UPC246351350, BSSID: 80:f5:03:a6:74:13, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 235924337, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 8: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -92, frequency: 2462, timestamp: 235924348, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 9 to mScanResults
V/ScoreHelper(  905): Only print Top 10 in ApScanList
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  72, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  72, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  71, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-91], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                     UPC246351350 [80:f5:03:a6:74:13], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  0 [-92], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0,
V/ScoreHelper(  905):  + ScoreResult:  68, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (9) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43c8b4f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{423080f8: PendingIntentRecord{4232e228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=245134, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43c8b4f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4393ec80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41cef980: PendingIntentRecord{4246a148 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=250852, Int=0
,D/PMS     (  905): acquireWL(441cc780): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): releaseWL(4393ec80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(433af1f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(441cc780): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(433af1f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  905): acquireWL(447c3da8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(447c3da8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] 80:f5:03:a6:74:13 freq=2462 level=-90
I/wpa_supplicant( 1136): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=114 entropy=98
D/wpa_supplicant( 1136): Add randomness: count=115 entropy=99
D/wpa_supplicant( 1136): Add randomness: count=116 entropy=100
D/wpa_supplicant( 1136): Add randomness: count=117 entropy=101
D/wpa_supplicant( 1136): Add randomness: count=118 entropy=102
D/wpa_supplicant( 1136): Add randomness: count=119 entropy=103
D/wpa_supplicant( 1136): Add randomness: count=120 entropy=104
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[5] 80:f5:03:a6:74:13 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[6] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELE,CT_BSSID CMD...
D/wpa_supplicant( 1136): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 5: 80:f5:03:a6:74:13 ssid='UPC246351350' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
D/wpa_supplicant( 1136): 6: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
,I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] 80:f5:03:a6:74:13 freq=2462 level=-90
I/wpa_supplicant( 1136): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-91
,D/wpa_supplicant( 1136): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=121 entropy=105
D/wpa_supplicant( 1136): Add randomness: count=122 entropy=106
D/wpa_supplicant( 1136): Add randomness: count=123 entropy=107
D/wpa_supplicant( 1136): Add randomness: count=124 entropy=108
D/wpa_supplicant( 1136): Add randomness: count=125 entropy=109
D/wpa_supplicant( 1136): Add randomness: count=126 entropy=110
D/wpa_supplicant( 1136): Add randomness: count=127 entropy=111
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[5] 80:f5:03:a6:74:13 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[6] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1136): reply (1040) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-48
I/wpa_supplicant( 1136): tsf=0000000253354734
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-57
I/wpa_supplicant( 1136): tsf=0000000253354761
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2427
I/wpa_supplicant( 1136): level=-77
I/wpa_supplicant( 1136): tsf=0000000253354772
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000253354781
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=8
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000253354801
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC5999698
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=9
I/wpa_supplicant( 1136): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000235924327
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=WDA83
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=10
I/wpa_supplicant( 1136): bssid=80:f5:03:a6:74:13
I/wpa_supplicant( 1136): freq=2462
I/wpa_supplicant( 1136): level=-90
I/wpa_supplicant( 1136): tsf=0000000253354791,
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC246351350
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=11
I/wpa_supplicant( 1136): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1136): freq=2462
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000253354813
I/wpa_supplicant( 1136): flags=[WPA2-PSK-
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiP2pService(  905): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 253354734, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 253354761, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 253354772, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 253354781, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 253354801, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -91, frequency: 2412, timestamp: 235924327, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: UPC246351350, BSSID: 80:f5:03:a6:74:13, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 253354791, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 7: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -91, frequency: 2462, timestamp: 253354813, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 8 to mScanResults
,V/ScoreHelper(  905):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  74, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  7 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  74, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  7 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-91], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                     UPC246351350 [80:f5:03:a6:74:13], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (8) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1136): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] 80:f5:03:a6:74:13 freq=2462 level=-90
I/wpa_supplicant( 1136): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=128 entropy=112
D/wpa_supplicant( 1136): Add randomness: count=129 entropy=113
D/wpa_supplicant( 1136): Add randomness: count=130 entropy=114
D/wpa_supplicant( 1136): Add randomness: count=131 entropy=115
D/wpa_supplicant( 1136): Add randomness: count=132 entropy=116
D/wpa_supplicant( 1136): Add randomness: count=133 entropy=117
D/wpa_supplicant( 1136): Add randomness: count=134 entropy=118
D/wpa_supplicant( 1136): Add randomness: count=135 entropy=119
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[5] 80:f5:03:a6:74:13 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[6] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136),: wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 3: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 6: 80:f5:03:a6:74:13 ssid='UPC246351350' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
D/wpa_supplicant( 1136): 7: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1136): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] 80:f5:03:a6:74:13 freq=2462 level=-90
I/wpa_supplicant( 1136): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=136 entropy=120
D/wpa_supplicant( 1136): Add randomness: count=137 entropy=121
D/wpa_supplicant( 1136): Add randomness: count=138 entropy=122
D/wpa_supplicant( 1136): Add randomness: count=139 entropy=123
D/wpa_supplicant( 1136): Add randomness: count=140 entropy=124
D/wpa_supplicant( 1136): Add randomness: count=141 entropy=125
D/wpa_supplicant( 1136): Add randomness: count=142 entropy=126
D/wpa_supplicant( 1136): Add randomness: count=143 entropy=127
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=,1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[5] 80:f5:03:a6:74:13 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[6] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1136): reply (1073) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-48
I/wpa_supplicant( 1136): tsf=0000000270734390
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-57
I/wpa_supplicant( 1136): tsf=0000000270734417
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2427
I/wpa_supplicant( 1136): level=-77
I/wpa_supplic,ant( 1136): tsf=0000000270734428
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000270734438
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=8
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000270734458
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC5999698
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=10
I/wpa_supplicant( 1136): bssid=80:f5:03:a6:74:13
I/wpa_supplicant( 1136): freq=2462
I/wpa_supplicant( 1136): level=-90
I/wpa_supplicant( 1136): tsf=0000000270734448
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC246351350
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=11
I/wpa_supplicant( 1136): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1136): freq=2462
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000270734482
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=12
I/wpa_supplicant( 1136): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-87
I/wpa_supplicant( 1136): tsf=0000000270734468
D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 270734390, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 270734417, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 270734428, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 270734438, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 270734458, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC246351350, BSSID: 80:f5:03:a6:74:13, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 270734448, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -91, frequency: 2462, timestamp: 270734482, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): 7: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2437, timestamp: 270734468, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 8 to mScanResults
,V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  72, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  72, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  72, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-87], Tx: 13, Freq:  5 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                     UPC246351350 [80:f5:03:a6:74:13], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (8) end of scan result ==
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1136): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-90
I/wpa_supplicant( 1136): [NULL] 80:f5:03:a6:74:13 freq=2462 level=-90
I/wpa_supplicant( 1136): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=144 entropy=128
D/wpa_supplicant( 1136): Add randomness: count=145 entropy=129
D/wpa_supplicant( 1136): Add randomness: count=146 entropy=130
D/wpa_supplicant( 1136): Add randomness: count=147 entropy=131
D/wpa_supplicant( 1136): Add randomness: count=148 entropy=132
D/wpa_supplicant( 1136): Add randomness: count=149 entropy=133
D/wpa_supplicant( 1136): Add randomness: count=150 entropy=134
D/wpa_supplicant( 1136): Add randomness: count=151 entropy=135
D/wpa_supplicant( 1136): Add randomness: count=152 entropy=136
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[5] 80:f5:03:a6:74:13 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[6] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() ,is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 3: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 6: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
D/wpa_supplicant( 1136): 7: 80:f5:03:a6:74:13 ssid='UPC246351350' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
D/wpa_supplicant( 1136): 8: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1136): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-90
I/wpa_supplicant( 1136): [NULL] 80:f5:03:a6:74:13 freq=2462 level=-90
I/wpa_supplicant( 1136): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=153 entropy=137
D/wpa_supplicant( 1136): Add randomness: count=154 entropy=138
D/wpa_supplicant( 1136): Add randomness: count=155 entropy=139
D/wpa_supplicant( 1136): Add randomness: count=156 entropy=140
D/wpa_supplicant( 1136): Add randomness: count=157 entropy=141
D/wpa_supplicant( 1136): Add randomness: count=158 entropy=142
D/wpa_supplicant( 1136): Add randomness: count=159 entropy=143
D/wpa_supplicant( 1136): Add randomness: count=160 entropy=144
D/wpa_supplicant( 1136): Add randomness: count=161 entropy=145
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=,0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[5] 80:f5:03:a6:74:13 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[6] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=,1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1136): reply (1204) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-48
I/wpa_supplicant( 1136): tsf=0000000288174473
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-57
I/wpa_supplicant( 1136): tsf=0000000288174501
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2427
I/wpa_supplicant( 1136): level=-73
I/wpa_supplicant( 1136): tsf=0000000288174513
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000288174543
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=8
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000288174533
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC5999698
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=10
I/wpa_supplicant( 1136): bssid=80:f5:03:a6:74:13
I/wpa_supplicant( 1136): freq=2462
I/wpa_supplicant( 1136): level=-90
I/wpa_supplicant( 1136): tsf=0000000288174523
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC246351350
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=11
I/wpa_supplicant( 1136): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1136): freq=2462
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000288174576
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=12
I/wpa_supplicant( 1136): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-87
I/wpa_supplicant( 1136): tsf=0000000288174553
,D/WirelessDisplayService(  905): getDiscoveryDongleList
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 288174473, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 288174501, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 288174513, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 288174543, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 288174533, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  905): 5: scan result = SSID: UPC246351350, BSSID: 80:f5:03:a6:74:13, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 288174523, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 6: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -91, frequency: 2462, timestamp: 288174576, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 7: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2437, timestamp: 288174553, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 8: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 288174563, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 9 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  83, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  71, AP:                     UPC246351350 [80:f5:03:a6:74:13], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  70, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  70, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  905):  + ScoreResult:  70, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-87], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  66, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  0 [-90], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
,D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (9) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList,
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42579548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42579548): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
,D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(424f5c60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{423080f8: PendingIntentRecord{4232e228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=305134, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(424f5c60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1136): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1136): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-90
I/wpa_supplicant( 1136): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-91
I/wpa_supplicant( 1136): [NULL] 76:04:2b:1b:09:43 freq=2437 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=162 entropy=146
D/wpa_supplicant( 1136): Add randomness: count=163 entropy=147
D/wpa_supplicant( 1136): Add randomness: count=164 entropy=148
D/wpa_supplicant( 1136): Add randomness: count=165 entropy=149
D/wpa_supplicant( 1136): Add randomness: count=166 entropy=150
D/wpa_supplicant( 1136): Add randomness: count=167 entropy=151
D/wpa_supplicant( 1136): Add randomness: count=168 entropy=152
D/wpa_supplicant( 1136): Add randomness: count=169 entropy=153
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP 76:04:2b:1b:09:43 type 0 added
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[5] 80:f5:03:a6:74:13 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[6] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[7] 76:04:2b:1b:09:43 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 9
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1136): wpa_s->,br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 0
I/wpa_supplicant( 1136): wpa_s->is_screen_on 0
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1136): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1136): 5: a0:c5:62:7a:49:96 ssid='UPC243894600' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
D/wpa_supplicant( 1136): 6: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1136): 7: 76:04:2b:1b:09:43 ssid='Lenovo TAB 2 A7-30H' wpa_ie_len=0 rsn_ie_len=0 wapi_ie_len=0 caps=0x421
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1136): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1136): nl80211: Received scan results (8 BSSes)
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1136): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-88
I/wpa_supplicant( 1136): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-90
I/wpa_supplicant( 1136): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-91
I/wpa_supplicant( 1136): [NULL] 76:04:2b:1b:09:43 freq=2437 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=170 entropy=154
D/wpa_supplicant( 1136): Add randomness: count=171 entropy=155
D/wpa_supplicant( 1136): Add randomness: count=172 entropy=156
D/wpa_supplicant( 1136): Add randomness: count=173 entropy=157
D/wpa_supplicant( 1136): Add randomness: count=174 entropy=158
D/wpa_supplicant( 1136): Add randomness: count=175 entropy=159
D/wpa_supplicant( 1136): Add randomness: count=176 entropy=160
D/wpa_supplicant( 1136): Add randomness: count=177 entropy=161
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): W,PS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP 76:04:2b:1b:09:43 type 0 added
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[4] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[5] 80:f5:03:a6:74:13 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[6] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[7] 76:04:2b:1b:09:43 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): clear disabled list - type=1
I/wpa_supplicant( 1136): No suitable network found
W/wpa_supplicant( 1136): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1136): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1136): reply (1322) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-48
I/wpa_supplicant( 1136): tsf=00000003055947,37
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-57
I/wpa_supplicant( 1136): tsf=0000000305594763
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2427
I/wpa_supplicant( 1136): level=-77
I/wpa_supplicant( 1136): tsf=0000000305594774
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000305594794
I/wpa_supplicant( 1136): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=UPC Wi-Free
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=8
I/wpa_supplicant( 1136): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-88
I/wpa_supplicant( 1136): tsf=0000000305594804
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC5999698
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=10
I/wpa_supplicant( 1136): bssid=80:f5:03:a6:74:13
I/wpa_supplicant( 1136): freq=2462
I/wpa_supplicant( 1136): level=-90
I/wpa_supplicant( 1136): tsf=0000000288174523
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC246351350
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=11
I/wpa_supplicant( 1136): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1136): freq=2462
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000305594826
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=12
I/wpa_supplicant( 1136): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-87
I/wpa_supplicant( 1136): tsf=0000000288174553
,D/WifiP2pService(  905): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  905): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 305594737, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 305594763, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 305594774, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2437, timestamp: 305594794, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 305594804, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC246351350, BSSID: 80:f5:03:a6:74:13, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 288174523, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  905): 6: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -91, frequency: 2462, timestamp: 305594826, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 7: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2437, timestamp: 288174553, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): 8: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 305594783, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 9: scan result = SSID: Lenovo TAB 2 A7-30H, BSSID: 76:04:2b:1b:09:43, capabilities: [WPS][ESS], level: -91, frequency: 2437, timestamp: 305594814, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  905): add 10 to mScanResults
,V/ScoreHelper(  905): Only print Top 10 in ApScanList
V/ScoreHelper(  905):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  905):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                     UPC246351350 [80:f5:03:a6:74:13], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  71, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  70, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  70, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-88], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  70, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-87], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  905):  + ScoreResult:  66, AP:                     UPC243894600 [a0:c5:62:7a:49:96], Rssi:  0 [-90], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0,
V/ScoreHelper(  905):  + ScoreResult:  66, AP:              Lenovo TAB 2 A7-30H [76:04:2b:1b:09:43], Rssi:  0 [-91], Tx: 13, Freq:  3 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  905):  + computeScore(NG700): 1
D/WifiStateMachine(  905): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (10) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/jxcore-log( 4374): --= Surplus to requirements =--,
I/jxcore-log( 4374): 
I/jxcore-log( 4374): ****TEST TOOK:  ms ****
I/jxcore-log( 4374): 
,I/jxcore-log( 4374): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 4374): 
,E/cutils-trace( 4723): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4723): ====startRecUseTime====
D/htc.customization.log.level( 4723):  is 
,W/CustomizationLogLevel( 4723): Level value is invalid, use default level 2
,D/CustomizationManager( 4723):  Read ACC file spent 0.118 (s)
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__M27
,D/CIDMapFileReader( 4723): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4723): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 4723): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4723): Parsing tag category name = system
,I/CustomizationCIDLoader( 4723): Parsing tag category name = application
I/CustomizationCIDLoader( 4723): Parsing tag category name = SettingsProvider,
I/CustomizationCIDLoader( 4723): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 4723): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4723): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4723): Parsing tag category name = Settings
D/CustomizationManager( 4723):  Read CID file spent 0.168 (s),
,D/CustomizationManager( 4723):  All configurations done spent 0.168 (s)
,W/HtcNativeFlag( 4723): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4723): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4723): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4723): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4723, uid=2000 user=0
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
,D/Process (  905): killProcessQuiet, pid=4374
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,I/ActivityManager(  905): Killing 4374:com.test.thalitest/u0a189 (adj 0): stop com.test.thalitest
,W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  905):   Force finishing activity ActivityRecord{42012890 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  905): Copying FileAsset 0x6ec10c30 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1212): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 4374 uid 10189
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1605): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1605): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1901): Unregistering com.test.thalitest
,E/acms    ( 1901): Could not unregister removed application com.test.thalitest
,I/dalvikvm-heap( 4113): Grow heap (frag case) to 13.498MB for 1821008-byte allocation
,W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
,D/VoicemailCleanupService( 1302): Cleaning up data for package: com.test.thalitest
I/Launcher( 1275): Deferring update until onResume
,D/Launcher( 1275): waitUntilResume // bindAppsRemoved
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowState(  905): WIN DEATH: Window{422d74b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputDispatcher(  905): channel '422d74b8 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  905): channel '422d74b8 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
D/WifiService(  905): Client connection lost with reason: 4
,W/InputDispatcher(  905): Attempted to unregister already unregistered input channel '422d74b8 com.test.thalitest.MainActivity (s)'
,W/GeofencerStateMachine( 1426): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
D/PMS     (  905): acquireWL(441e0a78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1426 10028 null
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/WindowManager(  905): WINDOW DIED Window{422d74b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
D/PMS     (  905): releaseWL(441e0a78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
,D/PackageBroadcastService( 1226): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,W/SystemReader( 1259): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/ActivityManager(  905): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4738 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,W/Parcel  ( 1259): Reading a NULL string not supported here.
,E/ExternalAccountType( 1335): Unsupported attribute readOnly
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
,D/PhoneApp( 1248): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  905): Delaying start of: ServiceRecord{4414aa98 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/MultiDex( 4738): install
,I/MultiDex( 4738): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/PeopleContactsSync( 1226): CP2 sync disabled
,I/MultiDex( 4738): loading existing secondary dex files
,I/MultiDex( 4738): load found 1 secondary dex files
,I/MultiDex( 4738): install done
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1226, uid=10028, userID:0
,I/ActivityManager(  905): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4755 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/PMS     (  905): acquireWL(43e37f08): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
I/Icing   ( 1226): doRemovePackageData com.test.thalitest
,D/PMS     (  905): releaseWL(43e37f08): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ProviderInstaller( 4738): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
,I/MultiDex( 4755): install
,I/MultiDex( 4755): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4755): loading existing secondary dex files
,I/MultiDex( 4755): load found 1 secondary dex files
,I/MultiDex( 4755): install done
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1454): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ProviderInstaller( 4755): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/[PluginManager]RegisterService( 1454): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(42eb9eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42eb9eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  905): killProcessQuiet, pid=4337
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1275): action: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  905): Killing 4337:com.android.settings:remote/1000 (adj 15): empty #17
,I/IcingCorporaProvider( 2913): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  905): Recipient 4337
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4775 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,E/SQLiteDBG( 2913): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63d2c7d0
,W/dalvikvm( 2913): threadid=16: thread exiting with uncaught exception (group=0x41699e30)
,E/ActivityManager(  905): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2913): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2913): Process: com.google.android.googlequicksearchbox:search, PID: 2913
E/AndroidRuntime( 2913): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 2913): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2913): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2913): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
E/AndroidRuntime( 2913): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/AndroidRuntime( 2913): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
E/AndroidRuntime( 2913): 	at cid.d(PG:192)
E/AndroidRuntime( 2913): 	at clo.g(PG:594)
E/AndroidRuntime( 2913): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2913): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2913): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2913): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2913): 	at clr.tL(PG:827)
E/AndroidRuntime( 2913): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2913): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2913): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2913): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2913): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2913): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Process ( 2913): killProcess, pid=2913
,D/Process ( 2913): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
,E/SQLiteLog( 4738): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 4738): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca0c340
,E/DriveAsyncService( 4738): disk I/O error (code 3850)
E/DriveAsyncService( 4738): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4738): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4738): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4738): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4738): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4738): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4738): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4738): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4738): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4738): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4738): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4738): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4738): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  905): Recipient 2913
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  905): Client com.google.android.googlequicksearchbox (pid 2913): Died!
D/WifiService(  905): Client connection lost with reason: 4
,I/ActivityManager(  905): Process com.google.android.googlequicksearchbox:search (pid 2913) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
,E/SQLiteLog( 4738): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
,E/SQLiteDBG( 4738): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca0c340
,E/DocListDatabase( 4738): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4738): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4738): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4738): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4738): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4738): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4738): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4738): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4738): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4738): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4738): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4738): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4738): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4738): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4738): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4738): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4738): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4738): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4738): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4738): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4738): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4738): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4738): threadid=1: thread exiting with uncaught exception (group=0x41699e30)
,E/ActivityManager(  905): App crashed! Process: com.google.android.gms.drive
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
,E/AndroidRuntime( 4738): FATAL EXCEPTION: main
E/AndroidRuntime( 4738): Process: com.google.android.gms.drive, PID: 4738
E/AndroidRuntime( 4738): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4738): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4738): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4738): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4738): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4738): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4738): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4738): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4738): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4738): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4738): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4738): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4738): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4738): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4738): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4738): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4738): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4738): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4738): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4738): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4738): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4738): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4738): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4738): 	... 10 more
D/Process ( 4738): killProcess, pid=4738
D/Process ( 4738): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
,W/PackageManager(  905): Unable to load service info ResolveInfo{425f4528 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  905): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  905): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  905): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  905): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  905): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  905): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteDatabase( 4775): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4775): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4775): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4775): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4775): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4775): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4775): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4775): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4775): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4775): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4775): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4775): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4775): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4775): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4775): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4775): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4775): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4775): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4775): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4775): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4775): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4775): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4775): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4775): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4775): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4775): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4775): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4775): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4775): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4775): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4775): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4775): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4775): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4775): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4775): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4775): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4775): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4775): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4775): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4775): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4775): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4775): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4775): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4775): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4775): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4775): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4775): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4775): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4775): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4775): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4775): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4775): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4775): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4775): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4775): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4775): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4775): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4775): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4775): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4775): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4775): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4775): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4775): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4775): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4775): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4775): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4775): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4775): Opened ClientFlag.db in read-only mode
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4738
I/ActivityManager(  905): Process com.google.android.gms.drive (pid 4738) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 10857ms
,E/SQLiteDatabase( 4775): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4775): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185),
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4775): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4775): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4775): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4775): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4775): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4775): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4775): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4775): threadid=11: thread exiting with uncaught exception (group=0x41699e30)
,E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4775): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4775): Process: com.google.android.apps.docs, PID: 4775
E/AndroidRuntime( 4775): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4775): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4775): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4775): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4775): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4775): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4775): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4775): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
,I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4796 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4775): killProcess, pid=4775
,D/Process ( 4775): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  905): start
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4775
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/Process (  905): killProcessQuiet, pid=4422
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
I/ActivityManager(  905): Killing 4422:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4775) has died.
I/ActivityManager(  905): Recipient 4422
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,W/ContextImpl( 4796): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4810 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4796): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4796): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4796): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4796): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4796): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4796): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4796): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4796): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4796): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4796): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4796): threadid=10: thread exiting with uncaught exception (group=0x41699e30)
,E/ActivityManager(  905): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4796): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4796): Process: com.android.keychain, PID: 4796
E/AndroidRuntime( 4796): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4796): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4796): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4796): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4796): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4796): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4796): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4796): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4796): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4796): killProcess, pid=4796
,D/Process ( 4796): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453034527952.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  905): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  905): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  905): 	... 4 more
,I/ActivityManager(  905): Recipient 4796
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Process com.android.keychain (pid 4796) has died.
,W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20664ms
,D/AppTag  ( 4810): getInstance(Context context)
,D/AppTag  ( 4810): getInstance(Context context)
,D/AppTag  ( 4810): onCreate()
,D/PMS     (  905): acquireWL(43d1fa60): PARTIAL_WAKE_LOCK  AsyncService 0x1 4113 10160 null
,I/dalvikvm-heap( 4113): Grow heap (frag case) to 15.201MB for 1821008-byte allocation
D/PMS     (  905): releaseWL(43d1fa60): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4828 uid=10098 gids={50098, 3003, 5012}
,I/dalvikvm-heap( 4113): Grow heap (frag case) to 16.936MB for 1821008-byte allocation
,I/DeviceManagement( 4828): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4828 dbg=false s=true
,I/DeviceManagement( 4828): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4828): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4828): WorkflowService: Starting workflow service
I/DeviceManagement( 4828): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41af9f88] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4828): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4828): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4828): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4828): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  905): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4842 uid=10099 gids={50099, 3003, 5012}
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41b5ce70 +
,I/Prism.WidgetManager( 1275): onLoadItems() +
,I/DeviceManagement( 4828): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4828): SessionStateController: Checking invariants...
,D/Documents( 4842): Loading roots for com.android.providers.downloads.documents
,D/Documents( 4842): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 4842): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4842): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4842): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4842): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4842): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4842): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4842): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4842): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4842): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4842): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4842): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4842): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4842): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4842): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4842): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4842): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4842): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4842): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4842): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4842): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4842): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4842): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4842): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4842): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4842): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4842): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4842): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4842): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4842): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4842): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4842): threadid=1: thread exiting with uncaught exception (group=0x41699e30)
,D/Process (  905): killProcessQuiet, pid=3854
E/AndroidRuntime( 4842): FATAL EXCEPTION: main
E/AndroidRuntime( 4842): Process: com.android.documentsui, PID: 4842
E/AndroidRuntime( 4842): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4842): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4842): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4842): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4842): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4842): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4842): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4842): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4842): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4842): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4842): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4842): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4842): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4842): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4842): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4842): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4842): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4842): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4842): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4842): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4842): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4842): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4842): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4842): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4842): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4842): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4842): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4842): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4842): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4842): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4842): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4842): 	... 10 more
I/ActivityManager(  905): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4856 uid=10023 gids={50023, 1028, 1015, 1023}
,I/ActivityManager(  905): Killing 3854:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,E/ActivityManager(  905): App crashed! Process: com.android.documentsui
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
,D/GCM     ( 1366): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/Process (  905): killProcessQuiet, pid=4474
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453034528277.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  905): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  905): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  905): 	... 4 more
I/ActivityManager(  905): Killing 4474:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,D/Process ( 4842): killProcess, pid=4842
,D/Process ( 4842): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Recipient 3854
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  905): Client com.google.android.music (pid 3854): Died!
I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Recipient 4842
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Process com.android.documentsui (pid 4842) has died.
,D/GCM     ( 1366): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/ExternalStorage( 4856): After updating volumes, found 1 active roots
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,E/SQLiteDatabase( 4828): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4828): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4828): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4828): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4828): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4828): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4828): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4828): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4828): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4828): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4828): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4828): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4828): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4828): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4828): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4828): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4828): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4828): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4828): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4828): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4828): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
I/ActivityManager(  905): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4873 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4828): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4828): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4828): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4828): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4828): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4828): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4828): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4828): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4828): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4828): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4828): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4828): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4828): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4828): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 4828): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41af9f88]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4828): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4828): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4828): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4828): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4828): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4828): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4828): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4828): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4828): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4828): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4828): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4828): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4828): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4828): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4828): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4828): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4828): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4828): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4828): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4828): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4828): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4828): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4828): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4828): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4828): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4828): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4828): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4828): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4828): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4474
I/DeviceManagement( 4828): WorkflowService: Stopping workflow service
,E/SQLiteDatabase( 4873): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 4873): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4873): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4873): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4873): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4873): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4873): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4873): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4873): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4873): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4873): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4873): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4873): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4873): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4873): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4873): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 4873): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 4873): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 4873): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 4873): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4873): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4873): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 4873): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4873): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4873): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4873): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4873): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4873): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4873): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4873): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4873): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4873): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4873): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4873): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4873): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4873): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4873): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 4873): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 4873): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 4873): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 4873): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4873): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 4873): Opened MyDB.db in read-only mode
,D/Process (  905): killProcessQuiet, pid=4490
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4490:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4490
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0

```
