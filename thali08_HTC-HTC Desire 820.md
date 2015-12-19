#### Test 50650278161ce7f_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  908):    returned true
E/cutils-trace( 4375): Error opening trace file: No such file or directory (2)
I/ActivityManager(  908): Waited long enough for: ServiceRecord{440ac6c0 u0 com.htc.htclocationservice/.AutoSettingService}
D/CustomizationManager( 4375): ====startRecUseTime====
D/htc.customization.log.level( 4375):  is 
W/CustomizationLogLevel( 4375): Level value is invalid, use default level 2
D/CustomizationManager( 4375):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4375): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4375): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4375): Parsing tag category name = system
I/CustomizationCIDLoader( 4375): Parsing tag category name = application
I/CustomizationCIDLoader( 4375): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4375): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4375): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4375): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4375): Parsing tag category name = Settings
D/CustomizationManager( 4375):  Read CID file spent 0.089 (s)
D/CustomizationManager( 4375):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 4375): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4375): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4375): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4375): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  908): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  908): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4375
D/PMS     (  908): acquireHCC(4237bb10): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 908 1000 null
D/PMS     (  908): acquireHCC(41ca4a00): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 908 1000 null
I/Intent  (  908): @test_code: getHtcIntentFlag: 0 obj: 1111888688
I/FeedHostManager( 1269): [onPause]
I/FeedProviderManager( 1269): onPause
I/FeedHostManager( 1269): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d414b8
I/SocialFeedProvider( 1269): +onPause
I/SocialFeedProvider( 1269): -onPause
D/PMS     (  908): acquireWL(4261cd18): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 908 1000 null
I/ActivityManager(  908): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4386 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1269): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4386): Binding Chromium to main looper Looper (main, tid 1) {41b45fd8}
I/LibraryLoader( 4386): Expected native library version number "",actual native library version number ""
I/chromium( 4386): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4386): Initializing chromium process, renderers=0
D/PMS     (  908): acquireWL(41f51280): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  908): acquireWL(4240a0d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  908): java.lang.Throwable: stack dump
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424e7a58:true
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4386): 1102430248: getState(). Returning 12
D/PMS     (  908): releaseWL(4240a0d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4386): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4386): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4386): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4386): Local Branch: 
I/Adreno-EGL( 4386): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4386): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4386):                  aa63bbd948f41d15fc72f585e
W/chromium( 4386): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4386): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4386): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4386): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4386): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4386): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4386): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4386): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4386): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4386): CordovaWebView is running on device made by: HTC
,W/AwContents( 4386): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  908): Disable input method client, pid=1269
,W/ResourceType( 4386): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4386): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b8d6d8, mServedView=org.apache.cordova.engine.SystemWebView{41b53340 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  908): Enable input method client, pid=4386
,W/AwContents( 4386): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  908): Displayed com.test.thalitest/.MainActivity: +266ms
,D/PMS     (  908): releaseWL(4261cd18): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/JsMessageQueue( 4386): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4386): JniHelper::setJavaVM(0x4161d048), pthread_self() = 1662866104
,D/JX-Cordova( 4386): jxcore cordova android initializing
,I/dalvikvm-heap( 4386): Grow heap (frag case) to 11.600MB for 144892-byte allocation
,D/PMS     (  908): acquireWL(42515af0): PARTIAL_WAKE_LOCK  Icing 0x1 2213 10028 null
,I/dalvikvm-heap( 4386): Grow heap (frag case) to 11.716MB for 217334-byte allocation
,D/PMS     (  908): releaseWL(42515af0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  908): acquireWL(423a2628): PARTIAL_WAKE_LOCK  Icing 0x1 2213 10028 null
,D/PMS     (  908): releaseWL(423a2628): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  908): acquireWL(42378d18): PARTIAL_WAKE_LOCK  Icing 0x1 2213 10028 null
,I/dalvikvm-heap( 4386): Grow heap (frag case) to 11.892MB for 325996-byte allocation
,D/PMS     (  908): releaseWL(42378d18): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  908): acquireWL(42571700): PARTIAL_WAKE_LOCK  Icing 0x1 2213 10028 null
,D/PMS     (  908): releaseWL(42571700): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/dalvikvm-heap( 4386): Grow heap (frag case) to 12.166MB for 488990-byte allocation
,I/dalvikvm-heap( 4386): Grow heap (frag case) to 12.573MB for 733480-byte allocation
,I/SensorManager(  908): mEventCount = 1050
,I/dalvikvm-heap( 4386): Grow heap (frag case) to 14.020MB for 1650320-byte allocation
,I/dalvikvm-heap( 4386): Grow heap (frag case) to 15.436MB for 2475476-byte allocation
,I/dalvikvm-heap( 4386): Grow heap (frag case) to 17.465MB for 3713210-byte allocation
,W/jxcore-log( 4386): Initializing JXcore engine
,W/jxcore-log( 4386): JXcore engine is ready
,W/CpuWake (  908): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  908): <<release mCpuPerf_Freq wakelock
D/PMS     (  908): releaseHCC(4237bb10): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,W/jxcore-log( 4386): Starting JXcore engine
D/PMS     (  908): releaseHCC(41ca4a00): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/ActivityManager(  908): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4433 uid=10077 gids={50077}
,D/PMS     (  908): acquireWL(42e8fb80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10077}
,V/AlarmManager(  908): sending alarm PendingIntent{42590c50: PendingIntentRecord{425fa7b8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450488686261, Int=60000
,D/PMS     (  908): releaseWL(42e8fb80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4433): SMSBackupAgentService started
,D/SMSBackup( 4433): Checking restore status
D/SMSBackup( 4433): Restore complete
,D/SMSBackup( 4433): cancelCheckAlarm
,D/SMSBackup( 4433): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  908): killProcessQuiet, pid=4194
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4194:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4194
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/jxcore-log( 4386): Platform android
W/jxcore-log( 4386): 
,W/jxcore-log( 4386): Process ARCH arm
W/jxcore-log( 4386): 
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/jxcore-log( 4386): JXcore Cordova bridge is ready!
I/jxcore-log( 4386): 
,W/jxcore-log( 4386): JXcore engine is started
I/chromium( 4386): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 4386): Skipped 137 frames!  The application may be doing too much work on its main thread.
,D/PMS     (  908): releaseWL(41f51280): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiDataStallTracker(  908): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  908): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  908): updateDataStallInfo: mDataStallTxRxSum={txSum=60 rxSum=48} preTxRxSum={txSum=59 rxSum=47}
D/WifiDataStallTracker(  908): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  908): onDataStallAlarm: tag=19749 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  908): startDataStallAlarm: tag=19750 delay=15s
D/PMS     (  908): acquireWL(42fe87b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{41df0388: PendingIntentRecord{4262e620 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105213, Int=0
D/PMS     (  908): releaseWL(42fe87b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4386): Toggling radios to true
I/jxcore-log( 4386): 
,D/BluetoothAdapter( 4386): enable(): BT is already enabled..!
,D/WifiManager( 4386): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  908): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  908): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  908): Settings:Agentvalue: 2
W/Settings:Agent(  908): >> traceCallingStack()
W/Settings:Agent(  908): Process.myPid(): 908
W/Settings:Agent(  908): Process.myTid(): 1272
W/Settings:Agent(  908): Process.myUid(): 1000
W/Settings:Agent(  908): 
W/Settings:Agent(  908): 
,W/System.err(  908): java.lang.Throwable: stack dump
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
W/Settings:Agent(  908): << traceCallingStack(): 1(ms)
,D/WifiManager( 4386): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  908): doBoolean: DISCONNECT
,D/WifiManager( 4386): reconnect: Base Package Name=com.test.thalitest, uid=10348
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/jxcore-log( 4386): Radios toggled
I/jxcore-log( 4386): 
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): TDLS: Tear down peers
,I/wpa_supplicant( 1136): wpa_driver_nl80211_disconnect(reason_code=3)
,D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  908): New client listening to asynchronous messages
D/WifiService(  908): setWifiEnabled: true pid=4386, uid=10348
E/WifiService(  908): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  908): isSprintWifiRestricted(): false
I/WifiService(  908): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  908): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4386): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4386): 
I/jxcore-log( 4386): Perf Test app loaded loaded
I/jxcore-log( 4386): 
I/Choreographer( 4386): Skipped 78 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4386): check test folder
I/jxcore-log( 4386): 
,I/jxcore-log( 4386): found test : ./testFindPeers.js
I/jxcore-log( 4386): 
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1136): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1136): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1136): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  908): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  908): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  908): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  908): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1136): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1136): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1136): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1136): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1136): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8426bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1136):    addr=c0:ff:d4:d3:aa:48
D/Tethering(  908): interfaceStatusChanged wlan0, false
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
I/wpa_supplicant( 1136): htc_wext_set,_TX_TRACKING - ret = 0
D/wpa_supplicant( 1136): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
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
D/WifiNative-wlan0(  908):    returned true
D/WifiPerfLock(  908): release()
D/WifiStateMachine(  908): PerfLock released for exiting ConnectedState
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): Power_Mode_Type mode = 0
I/wpa_supplicant( 1136): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  908):    returned true
,D/Tethering(  908): [isWifi] getHotspotEnabled: false
,I/jxcore-log( 4386): found test : ./testSendData.js
I/jxcore-log( 4386): 
,D/DhcpStateMachine(  908): [RunningState] Stop DHCP
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
,D/Tethering(  908): interfaceStatusChanged wlan0, false
,D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/ConnectivityService(  908): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  908): acquireWL(42d178a8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 908 1000 null
D/WifiP2pService(  908): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  908): doBoolean: RECONNECT
D/libc    (  908): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): Fast associate: Old scan results
I/wpa_supplicant( 1136): wpa_supplicant_scan enter
I/wpa_supplicant( 1136): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1136): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1136): wpa_supplicant_trigger_scan +
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1136): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  908):    returned true
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  908): Enter handleNetworkDisconnect
,D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=19750 mDataStallAlarmIntent=PendingIntent{4251e7b8: PendingIntentRecord{4262e620 android broadcastIntent}}
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  908): Provision feature enable=false
,D/ConnectivityService(  908): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): Power_Mode_Type mode = 0
I/wpa_supplicant( 1136): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 61
D/UsbnetStateTracker(  908): isAvailable+-
D/UsbnetStateTracker(  908): reconnect
,D/UsbnetStateTracker(  908): isAvailable+-
,D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  908):    returned true
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  908): default: reconnect()
D/MDST    (  908): default: setTeardownRequested(false)
D/MDST    (  908): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  908): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1887/10178)
D/ConnectivityService(  908): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  908): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  908): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3817): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  908): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WISPrService( 3817): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  365): [NET] entry_id:5   entry:0xb8cda948  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb8cdaad0  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb8cda868  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb8cdef70  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb8cdac98  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb8cded38  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb8cda468  removed 
D/libc    (  365): [NET] entry_id:8   entry:0xb8cdae40  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiService(  908): New client listening to asynchronous messages
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): handleConnectivityChange: resetting
D/ConnectivityService(  908): resetConnections(wlan0, 3)
D/ConnectivityService(  908): flush DNS cache for net 1(wlan0)
,D/PMS     (  908): acquireWL(42694ce0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10028 null
D/WISPrService( 3817): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3817): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1887/10178)
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/Nat464Xlat(  908): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  908): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  908): acquireWL(42d39d10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WirelessDisplayService(  908): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  908): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  908): startScan Pid: 908 Uid 1000
,D/WifiNative-wlan0(  908): doBoolean: SCAN
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1136): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  908):    returned false
D/PMS     (  908): acquireWL(4310fbf0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  908): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/BatSI   (  908): WIFI scan started for: 650a0300 uid:1000
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/PMS     (  908): releaseWL(42d39d10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  908): reportInetCondition for net -1, percentage: 0 by  (1376/10028)
D/PMS     (  908): releaseWL(42694ce0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
,D/ConnectivityService(  908): mActiveDefaultNetwork: -1
,D/ConnectivityService(  908): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  908): releaseWL(4310fbf0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/chromium( 4386): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  908): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/Tethering(  908): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  908): bSetPropertyMultiRAB:false
D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
D/CaptivePortalTracker(  908): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  908): NoActiveNetworkState,
,D/Tethering(  908): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/GpsLocationProvider(  908): [handleMessage] UPDATE_NETWORK_STATE,
D/GpsLocationProvider(  908): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  908): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  908): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1887/10178),
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10075)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1456/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1926/1000)
D/PMS     (  908): acquireWL(42d901b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
,I/Tethering(  908): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/ConnectivityHelper( 1269): [onReceive] WIFI(1): DISCONNECTED
I/Tethering(  908): ipv4Default null
I/Tethering(  908): No IPv4 upstream interface, giving up.
,D/Tethering(  908): TetherMasterSM: InitialState processMessage what=3
I/NetworkMonitor( 3882): type=WIFI subType= reason=null isConnected=false
D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.google.android.music (3882/10154)
D/PMS     (  908): releaseWL(42d901b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4277/10100)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4277/10100)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (2447/10021)
,I/ActivityManager(  908): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4455 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4455): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4455): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4455): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4455): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4455): Preparing secondary program dexes.
V/DexLibLoader( 4455): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4455): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4455): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4455): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4455): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4455): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4455): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4455): Dex already copied
D/OdexVerifier( 4455): Odex verification is skipped.
,V/DexLibLoader( 4455): Creating class loader
,V/DexLibLoader( 4455): Finished creating class loader
V/DexLibLoader( 4455): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4455): Dex already copied
D/OdexVerifier( 4455): Odex verification is skipped.
,V/DexLibLoader( 4455): Creating class loader
,V/DexLibLoader( 4455): Finished creating class loader
V/DexLibLoader( 4455): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4455): Dex already copied
D/OdexVerifier( 4455): Odex verification is skipped.
,V/DexLibLoader( 4455): Creating class loader
V/DexLibLoader( 4455): Finished creating class loader
V/DexLibLoader( 4455): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4455): Dex already copied
D/OdexVerifier( 4455): Odex verification is skipped.
,V/DexLibLoader( 4455): Creating class loader
,V/DexLibLoader( 4455): Finished creating class loader
,V/DexLibLoader( 4455): Verifying classes from secondary dexes.
,D/DexLibLoader( 4455): DexLibLoader.ensureDexLoaded took 20 ms
,W/dalvikvm( 4455): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4455): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4455): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4455): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4455): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4455): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4455): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1136): nl80211: Event message available
D/wpa_supplicant( 1136): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1136): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1136): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1136): nl80211: Survey data missing
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1136): Sorted scan results
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1136): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-49
I/wpa_supplicant( 1136): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1136): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-68
I/wpa_supplicant( 1136): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-84
I/wpa_supplicant( 1136): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-91
D/wpa_supplicant( 1136): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1136): Add randomness: count=8 entropy=0
D/wpa_supplicant( 1136): Add randomness: count=9 entropy=1
D/wpa_supplicant( 1136): Add randomness: count=10 entropy=2
D/wpa_supplicant( 1136): Add randomness: count=11 entropy=3
D/wpa_supplicant( 1136): Add randomness: count=12 entropy=4
D/wpa_supplicant( 1136): Add randomness: count=13 entropy=5
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=1 len=6
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
D/wpa_supplicant( 1136): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 1136): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1136): WPS: AP[3] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1136): wpa_supplicant_pick_network+
I/wpa_supplicant( 1136): Selecting BSS from priority group 1
I/wpa_supplicant( 1136): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1136): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1136): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1136): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1136):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1136):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-49
I/wpa_supplicant( 1136): Start print parameters
I/wpa_supplicant( 1136): wpa_s->wpa_state is 3
I/wpa_supplicant( 1136): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1136): isConcurrentMode() is 0
I/wpa_supplicant( 1136): wpa_s->br_mirror_sta,tus is 0
I/wpa_supplicant( 1136): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1136): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1136): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1136): wpa_s->reassociate is 1
I/wpa_supplicant( 1136): wpa_s->is_screen_on 1
I/wpa_supplicant( 1136): wpa_s->ifname wlan0
I/wpa_supplicant( 1136): End print parameters
I/wpa_supplicant( 1136): selected network = 1
D/wpa_supplicant( 1136): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb84284e8  current_ssid=0x0
D/wpa_supplicant( 1136): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1136): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1136): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1136): check if in concurrent case
I/wpa_supplicant( 1136): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1136): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1136): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1136): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1136): RSN: PMKSA cache search - network_ctx=0xb84284e8 try_opportunistic=0
D/wpa_supplicant( 1136): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1136): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1136): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1136): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1136): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1136): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1136): nl80211: Unsubscribe mgmt frames handle 0xb8427718 (mode change)
D/wpa_supplicant( 1136): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8427718
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8427718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8427718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8427718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8427718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8427718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8427718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8427718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8427718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8427718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Register frame type=0xd0 nl_handle=0xb8427718
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1136): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1136):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1136):   * freq=2412
D/wpa_supplicant( 1136):   * Auth Type 0
D/wpa_supplicant( 1136):   * WPA Versions 0x2
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1136): nl80211: Connect request send successfully
D/wpa_supplicant( 1136): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  908): doString: LIST_DONGLES
,D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  908): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1136): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1136): reply (908) for get BSS: id=0
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1136): freq=5220
I/wpa_supplicant( 1136): level=-50
I/wpa_supplicant( 1136): tsf=0000000107811077
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG7005g
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=1
I/wpa_supplicant( 1136): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-49
I/wpa_supplicant( 1136): tsf=0000000107811094
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=NG700
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=2
I/wpa_supplicant( 1136): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1136): freq=2427
I/wpa_supplicant( 1136): level=-68
I/wpa_supplicant( 1136): tsf=0000000107811099
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1136): ssid=Gonzos
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=3
I/wpa_supplicant( 1136): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-77
I/wpa_supplicant( 1136): tsf=0000000021841207
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1136): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=4
I/wpa_supplicant( 1136): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-84
I/wpa_supplicant( 1136): tsf=0000000107811102
I/wpa_supplicant( 1136): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC4688432
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=5
I/wpa_supplicant( 1136): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): freq=2412
I/wpa_supplicant( 1136): level=-50
I/wpa_supplicant( 1136): tsf=0000000107811090
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1136): ssid=01ABC
I/wpa_supplicant( 1136): ====
I/wpa_supplicant( 1136): id=6
I/wpa_supplicant( 1136): bssid=a0:c5:62:7a:49:96
I/wpa_supplicant( 1136): freq=2437
I/wpa_supplicant( 1136): level=-91
I/wpa_supplicant( 1136): tsf=0000000107811107
I/wpa_supplicant( 1136): flags=[WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1136): ssid=UPC243894600
I/wpa_supplicant( 1136): ####
,D/WirelessDisplayService(  908): getDiscoveryDongleList
,D/WifiStateMachine(  908): == begin of scan result ==
,D/WifiStateMachine(  908): == (7) end of scan result ==
,D/WirelessDisplayService(  908): getDiscoveryDongleList
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  908): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 107811077, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 2412, timestamp: 107811094, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/WifiStateMachine(  908): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -68, frequency: 2427, timestamp: 107811099, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -77, frequency: 2437, timestamp: 21841207, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 107811102, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 107811090, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 6: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 107811107, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): add 7 to mScanResults
D/BatSI   (  908): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  908): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,W/dalvikvm( 4455): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4455): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1136): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1136): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1136): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1136): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1136): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1136): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1136): nl80211: if_removed already cleared - ignore event
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
D/Tethering(  908): interfaceStatusChanged wlan0, false
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
D/wpa_supplicant( 1136): Add randomness: count=14 entropy=6
I/wpa_supplicant( 1136): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1136): TDLS: Remove peers on association
D/wpa_supplicant( 1136): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1136): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1136): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1136): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
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
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1136): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1136): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1136): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1136): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1136): Get randomness: len=32 entropy=7
D/WifiMonitor(  908): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  908): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  908): WifiMonitor:getFreqFromEventString() 2412
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/HTCRequest(  908): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  908): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  908): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  908): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
,D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  908): Enter handleAssociatedWithEvent
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  908): Associated
D/WifiStateMachine(  908): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  908): Exit handleAssociatedWithEvent
D/WifiStateMachine(  908): BSSID was changed, update WiFi database
D/Tethering(  908): interfaceLinkStateChanged wlan0, true
D/Tethering(  908): interfaceStatusChanged wlan0, true
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
D/Tethering(  908): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WifiStateMachine(  908): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  908): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  908): This record is existed, only update it...
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1136): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb84279f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1136):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1136): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1136): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f0db4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1136):    broadcast key
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1136): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1136): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1136): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1136): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1136): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiApDatabaseHandler(  908): updateConnectedAP...
E/wpa_supplicant( 1136): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1136): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1136): netlink: Operstate: linkmode=-1, operstate=6
,I/wpa_supplicant( 1136): set send_ind_to_ndc = 0
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
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1136): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1136): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1136): nl80211: if_removed already cleared - ignore event
D/Tethering(  908): interfaceLinkStateChanged wlan0, true
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/Tethering(  908): interfaceStatusChanged wlan0, true,
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  908): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WifiStateMachine(  908): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  908): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  908): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  908): This record is existed, only update it...
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  908): Provision feature enable=false
D/ConnectivityService(  908): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3817): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3817): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,E/FbInjectorInitializer( 4455): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/DhcpStateMachine(  908): [StoppedState] Start DHCP
D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
,D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): Power_Mode_Type mode = 1
I/wpa_supplicant( 1136): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  908):    returned null
E/WifiStateMachine(  908): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  908): doString: DRIVER WLS_BATCHING STOP
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  908):    returned null
D/WifiStateMachine(  908): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  908): acquireWL(43aae8d8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 908 1000 null
D/WifiStateMachine(  908): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  908): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424c8470 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424c8470 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4455): Verify
,D/WifiService(  908): New client listening to asynchronous messages
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4455): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4455): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4455): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  908): killProcessQuiet, pid=3864
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 3864:com.htc.mediamanager/u0a32 (adj 15): empty #17
,D/PMS     (  908): acquireWL(43adfa10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2213 10028 null
,D/PMS     (  908): acquireWL(432c5a38): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2213 10028 null
,D/PMS     (  908): releaseWL(43adfa10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1376): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2213/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
D/PMS     (  908): releaseWL(432c5a38): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2213/10028)
,D/AutoSetting( 1407): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  908): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4484 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1407/10053)
,D/AutoSetting( 1407): Util - no network available!
,D/AutoSetting( 1407): service - onCreate()
,D/AutoSetting( 1407): service - AddressCache: using context: com.htc.Weather
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1407/10053)
,D/LocationManagerService(  908): request 42401be0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  908): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1407): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/AutoSetting( 1407): service - mHandler: cancel location update
,D/AutoSetting( 1407): service -           changes count: 0
,I/ActivityManager(  908): Recipient 3864
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,W/fb4a(:<default>):UserScope( 4455): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 4455): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4484): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4484): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4484): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4484): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4455): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  908): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4512 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4484/10078)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4484/10078)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4484/10078)
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4455): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  908): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4537 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=4215
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
E/dalvikvm( 4455): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4455): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4455): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4455): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,I/ActivityManager(  908): Killing 4215:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
E/dalvikvm( 4455): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4455): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4455): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4455): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4455): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,E/dalvikvm( 4455): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4455): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4455): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4455): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4455): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4455): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4455): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4455): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4455): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
I/ActivityManager(  908): Recipient 4215
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  908): Client connection lost with reason: 4
,D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1136): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  908): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  908): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4455): Grow heap (frag case) to 9.965MB for 84664-byte allocation
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
,D/PMS     (  908): releaseWL(43aae8d8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4537): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): gateway: /192.168.1.1
,D/WifiNative-wlan0(  908): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1136): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  908): VerifyingLinkState enter
D/WifiStateMachine(  908): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  908): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  908): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -48, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,W/ContextImpl( 4537): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/WifiDataStallTracker(  908): startDataStallAlarm: tag=19752 delay=15s
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  908): WAN detection
V/NetworkPolicy(  908): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WISPrService( 3817): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  908): Provision feature enable=false
D/ConnectivityService(  908): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  908): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  908): default: teardown()
D/MDST    (  908): default: setTeardownRequested(true)
D/MDST    (  908): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1117): WifiActivity: 1
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/MDST    (  908): default: setTeardownRequested(true)
D/ConnectivityService(  908): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,I/dalvikvm-heap( 4455): Grow heap (frag case) to 9.990MB for 39954-byte allocation
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  908): syncGetConfiguredNetworks
,W/GAV2    ( 4537): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
E/ConnectivityService(  908): Unexpected mtu value: android.net.wifi.WifiStateTracker@424755c0
D/ConnectivityService(  908): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/ConnectivityService(  908): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  908): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,W/ContextImpl( 4537): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
D/ConnectivityService(  908): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  908): handleConnectivityChange: resetting
D/Nat464Xlat(  908): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  908): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4537): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  908): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  908):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [1][0][0]
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  908): sendGeneralBroadcastDelayed, restrictEnable=false
D/PMS     (  908): acquireWL(437e5e08): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  908): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4484/10078)
,I/dalvikvm-heap( 4455): Grow heap (frag case) to 10.066MB for 79892-byte allocation
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  908): acquireWL(4243b368): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2213 10028 null
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/PMS     (  908): releaseWL(437e5e08): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  908): acquireWL(426b3d00): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2213 10028 null
,D/PMS     (  908): releaseWL(4243b368): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2213/10028)
,I/CheckinService( 2213): Preparing to send checkin request
,I/EventLogService( 2213): Accumulating logs since 1450488639016
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,I/dalvikvm-heap( 4455): Grow heap (frag case) to 10.093MB for 28144-byte allocation
,I/GoogleHttpClient( 2213): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2213): Using GMS GoogleHttpClient
D/ConnectivityService(  908): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  908): getNetworkInfo networkType=9 called by com.google.android.gms (2213/10028)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.google.android.gms (2213/10028)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4537/10151)
,V/WebViewChromiumFactoryProvider( 4537): Binding Chromium to main looper Looper (main, tid 1) {41b4b2a8}
,I/LibraryLoader( 4537): Expected native library version number "",actual native library version number ""
,I/chromium( 4537): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4537): Initializing chromium process, renderers=0
,W/GLSUser ( 1376): GoogleAccountDataService.getToken()
,E/AudioManagerAndroid( 4537): BLUETOOTH permission is missing!
D/PMS     (  908): acquireWL(431e13b0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  908): releaseWL(431e13b0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/PMS     (  908): acquireWL(43726568): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1376): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,I/Adreno-EGL( 4537): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4537): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4537): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4537): Local Branch: 
I/Adreno-EGL( 4537): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4537): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4537):                  aa63bbd948f41d15fc72f585e
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/NSApplication( 4537): Starting up...
,I/dalvikvm-heap( 4455): Grow heap (frag case) to 10.280MB for 75760-byte allocation
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4537/10151)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4537/10151)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4370a798 u0 ReceiverList{4370a758 4455 com.facebook.katana/10026/u0 remote:436d7c00}}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4370a798 u0 ReceiverList{4370a758 4455 com.facebook.katana/10026/u0 remote:436d7c00}}
,W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4329b1c0 u0 ReceiverList{4329b160 4455 com.facebook.katana/10026/u0 remote:44102350}}
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/Process (  908): killProcessQuiet, pid=4012
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (4138/10160)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (4138/10160)
I/ActivityManager(  908): Killing 4012:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4012
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1887/10178)
,D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1887/10178)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/GCM     ( 1376): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1887/10178)
,D/wpa_supplicant( 1136): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1136): EAPOL: disable timer tick
,D/PMS     (  908): acquireWL(41d889e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1456 10028 null
,D/PMS     (  908): releaseWL(41d889e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1456): Unknown pending intent to remove.
D/PMS     (  908): acquireWL(4405a5f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1456 10028 null
,D/DotMatrix( 1611): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1611): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41c91ee0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/PMS     (  908): releaseWL(4405a5f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
W/CheckinRequestBuilder( 2213): awaiting user notification for token
I/RemoteViews.Performance( 1117): com.google.android.gms 1 6 2 12
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4455): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  908): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4592 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4455): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/MultiDex( 4592): install
,I/MultiDex( 4592): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4592): loading existing secondary dex files
,I/MultiDex( 4592): load found 1 secondary dex files
,I/MultiDex( 4592): install done
,I/ProviderInstaller( 4592): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1376): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (4592/10028)
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  908): releaseWL(42d178a8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  908): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  908): [AlarmQueuing] connectivity wifi: true
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  908): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  908): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  908): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  908): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  908): NoActiveNetworkState
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,V/Tethering(  908): bSetPropertyMultiRAB:false
,D/Tethering(  908): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/NetworkMonitor( 3882): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/PMS     (  908): acquireWL(43727f10): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/PMS     (  908): releaseWL(43727f10): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1887/10178)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.google.android.music (3882/10154)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4277/10100)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4484/10078)
I/Tethering(  908): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  908): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  908): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  908): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  908): Found interface wlan0
,D/Tethering(  908): TetherMasterSM: InitialState processMessage what=3
I/ConnectivityHelper( 1269): [onReceive] WIFI(1): CONNECTED
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/acms    ( 1926): Checking Certificates
I/acms    ( 1926): Checking Developer Certificates
I/acms    ( 1926): Checking Application Certificates
I/acms    ( 1926): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1926): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1926): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1926): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1926): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1926): Updating next query delay: 75600000
I/mlserverapp( 1926): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1926): cancelACMSProgrammedChecks
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.musicenhancer (3905/10051)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10075)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1926/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1456/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4277/10100)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
D/PMS     (  908): acquireWL(4230dbc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
D/PMS     (  908): releaseWL(4230dbc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (2447/10021)
,D/PMS     (  908): acquireWL(424916b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2213 10028 null
,D/PMS     (  908): releaseWL(424916b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1376): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/libc    ( 1376): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1376): [NET] getaddrinfo-,err=8
D/libc    ( 1376): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1376): [NET] getaddrinfo-, 1
,D/libc    ( 1376): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =6841 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
D/PMS     (  908): acquireWL(42434ec8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1376 10028 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2213/10028)
,D/AutoSetting( 1407): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4484): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/AutoSetting( 1407): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/MobileConnectivityChangeReceiver( 4484): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1407): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1407): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1407): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1407): service - handleMessage() setting current location null
D/AutoSetting( 1407): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1407): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1407/10053)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1407/10053)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 236
D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1376): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4537/10151)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (4138/10160)
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (4138/10160)
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1887/10178)
,I/dalvikvm-heap( 4138): Grow heap (frag case) to 13.499MB for 1821008-byte allocation
,D/libc    ( 1376): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1376): [NET] getaddrinfo-,err=8
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
D/PMS     (  908): acquireWL(42516110): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
D/PMS     (  908): releaseWL(42516110): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/Adreno-EGL( 4592): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4592): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4592): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4592): Local Branch: 
I/Adreno-EGL( 4592): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4592): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4592):                  aa63bbd948f41d15fc72f585e
,D/GCM     ( 1376): Connected
D/PMS     (  908): acquireWL(4241fff8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10028 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
D/PMS     (  908): releaseWL(42434ec8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1376/10028)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  908): handleInetConditionChange: starting a change hold
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
D/PMS     (  908): releaseWL(4241fff8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  908): acquireWL(4231d2f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10028 null
,I/Adreno-EGL( 4592): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4592): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4592): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4592): Local Branch: 
I/Adreno-EGL( 4592): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4592): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4592):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1376/10028)
,D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  908): handleInetConditionChange: currently in hold - not setting new end evt
,D/GCM     ( 1376): Message class mpf
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1376/10028)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  908): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
D/PMS     (  908): acquireWL(41d8cb18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
D/PMS     (  908): releaseWL(4231d2f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  908): releaseWL(41d8cb18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/Adreno-EGL( 4592): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4592): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4592): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4592): Local Branch: 
I/Adreno-EGL( 4592): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4592): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4592):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4592): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinTask( 2213): Sending checkin request (8843 bytes)
D/libc    ( 2213): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2213): [NET] getaddrinfo-,err=8
D/libc    ( 2213): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2213): [NET] getaddrinfo-, 1
,D/libc    ( 2213): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =4130 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 288
D/libc    (  365): [NET]res_nsend:resplen=84
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2213): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2213): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2213): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  908): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=9 [21][2][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,I/PMS     (  908): Going to sleep due to screen timeout...
,I/ActivityManager(  908): mThumbnailWidth=360, mThumbnailHeight=640
I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421ede10
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  908): pid=908, uid=1000
V/LightsService(  908): setLight #2: color=#0
D/qdlights(  908): set_light_buttons_func: on=0 brightness=0
V/LightsService(  908): setLight #0: color=#0
,W/BatSI   (  908): Couldn't get kernel wake lock stats
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421ede10, eanble = 0, strlen(mName) = 59
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422b4868
W/SensorService(  908): Listener[1] = com.htc.smartdim.sensor_eye@42614868
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/dalvikvm( 4386): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
W/dalvikvm( 4386): threadid=1: thread exiting with uncaught exception (group=0x41715e30)
,E/AndroidRuntime( 4386): FATAL EXCEPTION: main,
E/AndroidRuntime( 4386): Process: com.test.thalitest, PID: 4386
E/AndroidRuntime( 4386): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4386): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4386): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4386): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4386): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4386): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4386): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4386): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4386): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4386): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4386): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4386): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4386): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4386): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4386): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4386): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4386): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4386): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4386): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  908): App crashed! Process: com.test.thalitest
W/PMS     (  908): mWirelessDisplayManager is null
,D/WirelessDisplayService(  908): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  908): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/ActivityManager(  908):   Force finishing activity com.test.thalitest/.MainActivity
,D/PMS     (  908): acquireWL(440582a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
,D/PMS     (  908): releaseWL(440582a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null,
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [4][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  908): BroadcastRSSIForIMS, newrssi =-50 , oldRssi= -200
,D/SurfaceControl(  908): Excessive delay in blankDisplay() while turning screen off: 377ms
D/PMS     (  908): nativeSetInteractive:false
D/PMS     (  908): nativeSetInteractive:false done
D/PMS     (  908): nativeSetAutoSuspend:true
D/PMS     (  908): nativeSetAutoSuspend:true done
,D/PMS     (  908): acquireWL(42a38018): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 908 1000 null
,D/HABCtrl (  908): TPE algorithm. remove timeout.
,D/PMS     (  908): OOBE c monitor 11
,I/InputMethodManagerService(  908): screenObserver, isScreenOn=false
,D/NfcService( 1253): ScreenObserver: OFF
,D/NfcService( 1253): applyRouting - 0
I/InputMethodManagerService(  908): Disable input method client, pid=4386
D/PMS     (  908): acquireWL(440ac918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
,D/NfcService( 1253): applyRouting -2
D/PMS     (  908): acquireWL(43108a58): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  908): releaseWL(43108a58): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/WifiNative-wlan0(  908):    returned true
D/PMS     (  908): releaseWL(440ac918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
,V/KeyguardServiceDelegate(  908): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@436a9a70)
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/PMN     (  908): wakingUp
,V/KeyguardServiceDelegate(  908): **** SHOWN CALLED ****
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputManager(  908): Cancel all due to getting PMS screen off broadcast
I/WindowManager(  908): No lock screen! windowToken=null
D/PMN     (  908): onScreenOn
,D/ConnectivityService(  908): getNetworkInfo networkType=9 called by com.google.android.gms (2213/10028)
,D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.google.android.gms (2213/10028)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  908): startDataStallAlarm: tag=19753 delay=15s
D/AlarmManager(  908): ACTION_SCREEN_ON
I/AlarmManager(  908): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done recovering
I/AlarmManager(  908): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  908): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): SET_SCREEN_ON:On
I/wpa_supplicant( 1136): htc_wext_set_keepalive +
I/wpa_supplicant( 1136): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1136): getPrivFuncNum +	
I/wpa_supplicant( 1136): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1136): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1136): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1136): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  908):    returned true
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1611): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/MtpService( 2447): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/MtpService( 2447): [MTP][onReceive]-
,D/NfcService( 1253): applyRouting - 0
,D/AutoSetting( 1407): receiver - intent: android.intent.action.USER_PRESENT
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1136): WiFioffload: SignalStrength: =97
D/WirelessDisplayService(  908): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  908):    returned true
,D/NfcService( 1253): applyRouting -2
D/TetherSettings( 3817): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3817): Cust_ConnectToPC   : Internet_Sharing>true
I/ClockThread( 1117): stop update clock
D/        ( 3817): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3817): Cust_ConnectToPC   : spcsc>false
D/        ( 3817): Cust_ConnectToPC   : IPT>true
D/        ( 3817): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3817): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3817): hasRemovableStorageSlot: true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
D/PMS     (  908): acquireWL(430fcf38): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  908): releaseWL(430fcf38): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/SmartNS_Utility( 3817): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3817): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1407): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/PSReceiver( 3817): onReceive:android.intent.action.USER_PRESENT
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/ContextImpl( 3817): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/SRS_Proc(  372): ParamSet string: screen_state=on
I/SmartNS_PSService( 3817): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3817): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3817):  defaultType:0
D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,D/NetworkPolicy(  908): updateScreenOn: false
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4635 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/GLSUser ( 1376): GoogleAccountDataService.getToken()
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/DotMatrix( 1611): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/PMS     (  908): acquireWL(43a9e850): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1456 10028 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1860): onScreenOn: false
,D/PMS     (  908): releaseWL(43a9e850): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1860): onScreenOn: 1450488694220
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1860): onScreenOn: 1450488694222
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1376): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422b4868
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422b4868, eanble = 0, strlen(mName) = 91
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  908): Listener[0] = com.htc.smartdim.sensor_eye@42614868
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/ContextImpl( 4635): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMN     (  908): goingToSleep
D/PMS     (  908): acquireWL(42510690): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 908 1000 null
D/PMS     (  908): releaseWL(42a38018): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SmartSyncUtils( 4635): isEpsOn(), nState = 0
D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=19753 mDataStallAlarmIntent=PendingIntent{4249b8b8: PendingIntentRecord{4262e620 android broadcastIntent}}
D/PMS     (  908): acquireWL(440609e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4635 1000 null
D/AlarmManager(  908): ACTION_SCREEN_OFF
I/AlarmManager(  908): [AlarmQueuing] screen off now: 
I/AlarmManager(  908): [AlarmQueuing] data connection: true
,I/AlarmManager(  908): [AlarmQueuing] wifi connection: true
W/fb4a(:<default>):UserScope( 4455): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):UserScope( 4455): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1136): SET_SCREEN_ON:Off
I/wpa_supplicant( 1136): htc_wext_set_keepalive +
I/wpa_supplicant( 1136): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1136): getPrivFuncNum +	
I/wpa_supplicant( 1136): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1136): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1136): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1136): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1136): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  908): doBoolean: DRIVER SETSUSPENDMODE 1
,D/WifiNative-wlan0(  908):    returned true
,D/PMS     (  908): acquireWL(432c9670): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 908 1000 null
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(440609e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/DotMatrix( 1611): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1611): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2213): awaiting user notification for token
,I/RemoteViews( 1117): com.google.android.gms (false,0)
D/wpa_supplicant( 1136): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  908):    returned true
,V/SRS_Proc(  372): ParamSet string: screen_state=off
,D/PMS     (  908): releaseWL(432c9670): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/SmartSyncUtils( 4635): getMobilePolicyEnabled, result = true
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41ecc318 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,I/RemoteViews.Performance( 1117): com.google.android.gms 2 10 4 12
,D/Process (  908): killProcessQuiet, pid=4246
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  908): Killing 4246:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,D/NetworkPolicy(  908): updateScreenOn: false
,I/ActivityManager(  908): Recipient 4246
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ContactMessageStore( 1241): start background delete task...
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ContactMessageStore( 1241): size: 0 , 0
D/ContactMessageStore( 1241): Background delete complete
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
W/ActivityManager(  908): Activity pause timeout for ActivityRecord{41b3cd68 u0 com.test.thalitest/.MainActivity t2 f}
,D/Process (  908): killProcessQuiet, pid=4277
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
I/ActivityManager(  908): Killing 4277:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =14e0 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,W/ContextImpl( 4635): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/CheckinTask( 2213): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
W/GoogleHttpClient( 2213): Unable to close GMS GoogleHttpClient
D/SmartSyncUtils( 4635): isEpsOn(), nState = 0
D/SmartSyncUtils( 4635): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4635): isEpsOn(), nState = 0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2213/10028)
D/WifiService(  908): New client listening to asynchronous messages
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42614868
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 1
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42614868, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 0
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42614868, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42614868
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2213/10028)
E/ActivityThread(  908): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42624db0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42624db0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1611): [EventService] getTotalRam: 1873 Mb
,D/GCM     ( 1376): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  908): releaseWL(426b3d00): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/PMS     (  908): acquireWL(437cd818): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1456 10028 null
E/ActivityThread( 2213): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bf3a80 that was originally bound here
E/ActivityThread( 2213): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bf3a80 that was originally bound here
E/ActivityThread( 2213): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2213): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2213): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2213): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2213): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2213): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2213): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2213): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2213): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2213): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2213): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2213): 	at bks.a(SourceFile:298)
E/ActivityThread( 2213): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2213): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2213): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2213): 	at java.lang.Thread.run(Thread.java:864)
,D/PMS     (  908): releaseWL(437cd818): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1860): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1860): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1860): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1860): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1860): onScreenOff
,I/GCM     ( 1376): GCM config loaded
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  908): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  908): Find DNS Address www.htc.com/23.59.123.86
D/AutoSetting( 1407): service - mHandler: cancel location update
,D/AutoSetting( 1407): service -           changes count: 0
,I/ActivityManager(  908): Recipient 4277
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): releaseWL(43726568): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,E/fb4a(:<default>):LocalFbBroadcastManager( 4455): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4455/10026)
D/WifiStateMachine(  908): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  908): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,I/GAV2    ( 4537): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  908): acquireWL(4401cec8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1456 10028 null
,D/PMS     (  908): acquireWL(4405c6e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1456 10028 null
,D/PMS     (  908): releaseWL(4401cec8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  908): releaseWL(4405c6e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  908): Killing 4300:com.htc.backup/1000 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=4300
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Recipient 4300
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1531): service - handleMessage() stop self
,D/AutoSetting( 1531): service - onDestroy() END
,D/Process (  908): killProcessQuiet, pid=4263
,I/ActivityManager(  908): Killing 4263:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/AutoSetting( 1531): service - handleMessage() quit looper
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/ActivityManager(  908): Sleep timeout!  Sleeping now.
,D/PMS     (  908): releaseWL(42510690): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/ActivityManager(  908): Recipient 4263
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  908): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/ActivityManager(  908): Activity destroy timeout for ActivityRecord{41b3cd68 u0 com.test.thalitest/.MainActivity t2 f}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{42d1d390 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  908): acquireWL(4405a640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1611): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): releaseWL(4405a640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(43aa6ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=137289, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43aa6ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1407): service - mHandler: update timezone
,D/AutoSetting( 1531): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1531): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1531): service - onCreate()
W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1531): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1531): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1611): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1611): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1531): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1531): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1531): service - mHandler: update timezone
,D/AutoSetting( 1531): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1531): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1531): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1531): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1611): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1611): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41d01238 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 2 6 2 11
,D/PMS     (  908): acquireWL(4371a438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,D/GpsLocationProvider(  908): ALARM_XTRA_TIMEOUT
,D/AutoSetting( 1407): service - handleMessage() stop self
V/AlarmManager(  908): sending alarm PendingIntent{4245bb40: PendingIntentRecord{41c893d0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141179, Int=0
D/PMS     (  908): acquireWL(43719df0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
,V/AlarmManager(  908): sending alarm PendingIntent{43449148: PendingIntentRecord{425e7c50 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141721, Int=0
D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  908): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
,D/PMS     (  908): releaseWL(4371a438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/AutoSetting( 1407): service - handleMessage() quit looper
,D/PMS     (  908): acquireWL(43702758): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
,D/AutoSetting( 1407): service - onDestroy() END
D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =a1bb +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  908): releaseWL(43702758): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59,
D/libc    (  365): [NET]res_nsend:resplen=238
D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo_proxy-, success
I/global  (  908): call createSocket() return a new socket.
D/libc    (  908): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  908): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  908): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  908): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  908):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  908): releaseWL(43719df0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Process (  908): killProcessQuiet, pid=3905
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3905:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3905
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{43fa6100 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1531): service - handleMessage() stop self
,D/AutoSetting( 1531): service - onDestroy() END
,D/AutoSetting( 1531): service - handleMessage() quit looper
,I/ActivityManager(  908): Killing 4318:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=4318
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 4318
,D/PMS     (  908): acquireWL(42e50698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42e50698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1611): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/PMS     (  908): acquireWL(41ea1480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(41ea1480): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  908): acquireWL(41bb13b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=197290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(41bb13b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(421ea9c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10026}
V/AlarmManager(  908): sending alarm PendingIntent{423e8060: PendingIntentRecord{433c2088 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=228900, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{437d1208: PendingIntentRecord{41b3c7e0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450488767161, Int=1800000
,I/ActivityManager(  908): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4676 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  908): sending alarm PendingIntent{42493f40: PendingIntentRecord{42529930 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450488802625, Int=10800000
,D/PMS     (  908): acquireWL(41e8c7c8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2213 10028 null
,D/PMS     (  908): releaseWL(421ea9c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  908): acquireWL(42485868): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2213 10028 null
,I/EventLogService( 2213): Aggregate from 1450488691425 (log), 1450486967043 (data)
D/PMS     (  908): releaseWL(41e8c7c8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.aurora (4676/10047)
,D/PMS     (  908): releaseWL(42485868): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/Process (  908): killProcessQuiet, pid=4335
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4335:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4335
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2213/10028)
,D/PMS     (  908): acquireWL(41dac568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10026}
,V/AlarmManager(  908): sending alarm PendingIntent{420d9870: PendingIntentRecord{433c2088 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231546, Int=0
,D/PMS     (  908): releaseWL(41dac568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(437175e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(437175e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(425963f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=257290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(425963f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(4237acc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1611): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): releaseWL(4237acc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(41f5bc28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(41f5bc28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(423947e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=317290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(423947e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  908): acquireWL(425e6cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  908): n_update end
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1611): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PMS     (  908): releaseWL(425e6cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1376): GoogleAccountDataService.getToken()
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1376): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1376): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1611): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
W/GLSActivity( 1376): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1376): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1376): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1376): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1376): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1376): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1376): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1376): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1611): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,E/PlayEventLogger( 4102): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4102): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4102): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4102): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4102): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4102): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4102): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4102): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41fe8088 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 9 4 12
,D/libc    ( 4102): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4102): [NET] getaddrinfo-,err=8
D/libc    ( 4102): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4102): [NET] getaddrinfo-, 1
,D/libc    ( 4102): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =8bf6 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4102): [NET] getaddrinfo_proxy-, success
I/global  ( 4102): call createSocket() return a new socket.
D/libc    ( 4102): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4102): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4102): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4102): [NET] getaddrinfo-,err=8
,D/PMS     (  908): acquireWL(4257b5c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1611): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): releaseWL(4257b5c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  908): acquireWL(423ac410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=377290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(423ac410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/Process ( 4386): killProcess, pid=4386
,D/Process ( 4386): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/InputMethodManagerService(  908): Disable input method client, pid=4386
,I/ActivityManager(  908): Recipient 4386
I/ActivityManager(  908): Process com.test.thalitest (pid 4386) has died.
,I/WindowState(  908): WIN DEATH: Window{42e52bc8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  908): Client connection lost with reason: 4
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(42539660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42539660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1611): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(426a8fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
D/PMS     (  908): releaseWL(426a8fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1611): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42ce4278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=437289, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42ce4278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  908): acquireWL(42d1b390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42d1b390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(44073a20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(44073a20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  908): acquireWL(435e6630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=497290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(435e6630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(432b9ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(432b9ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4371bfd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=557290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4371bfd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43ae0480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10026}
V/AlarmManager(  908): sending alarm PendingIntent{43ab5858: PendingIntentRecord{4369e920 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=411201, Int=300000
,V/AlarmManager(  908): sending alarm PendingIntent{41dfabd8: PendingIntentRecord{424e1500 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=581292, Int=0
,D/PMS     (  908): acquireWL(431a2d78): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): releaseWL(43ae0480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(44031d30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
D/PMS     (  908): releaseWL(431a2d78): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  908): releaseWL(44031d30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  908): acquireWL(4324a6a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4324a6a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  353): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(43b25c98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=617290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43b25c98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1241): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1241): sku_id=99
D/ContactMessageStore( 1241): start background delete task...
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
,D/PMS     (  908): acquireWL(43c11310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43c11310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4313aea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=677289, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4313aea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(432ceb98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10026}
,V/AlarmManager(  908): sending alarm PendingIntent{43ab5858: PendingIntentRecord{4369e920 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=711201, Int=300000
,D/PMS     (  908): releaseWL(432ceb98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  908): acquireWL(43743600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43743600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4314e600): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=737290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4314e600): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(436a8178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41e3e380: PendingIntentRecord{4247fd78 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786114, Int=0
D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,D/PMS     (  908): releaseWL(436a8178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  908): Done.
,D/ConnectivityService(  908): Setting timer for 720seconds
,D/PMS     (  908): acquireWL(4319c148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4319c148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43b25030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=797289, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43b25030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43aeae08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43aeae08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(431df840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=857290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(431df840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(432b3228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(432b3228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42675380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=917290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42675380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43a96390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43a96390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43932890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=977290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43932890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43ab2998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10028}
,D/PMS     (  908): acquireWL(43c4d670): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1376 10028 null
,V/AlarmManager(  908): sending alarm PendingIntent{420054d8: PendingIntentRecord{425ed488 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1010076, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{42356af8: PendingIntentRecord{422e85b8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450489522898, Int=900000
V/AlarmManager(  908): sending alarm PendingIntent{4352c2f0: PendingIntentRecord{43728a28 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450489594368, Int=0
,D/PMS     (  908): releaseWL(43c4d670): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  908): acquireWL(42549648): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
,W/ContextImpl( 4635): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  908): releaseWL(42549648): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PowerUsageService( 4635): call getInstance()
,D/SmartSyncUtils( 4635): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4635): MY_DEBUG = false
,D/SmartSyncScreenOnOffTimeReceiver( 4635): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4635): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
D/PMS     (  908): acquireWL(432b5ad8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4635 1000 null
,D/PMS     (  908): releaseWL(43ab2998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4635): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4635): SettingOnTime = 1450504800000, randomSettingOnTime = 1450504601000
D/SmartSyncScreenOnOffTimeReceiver( 4635): SettingOffTime = 1450569600000, randomSettingOffTime = 1450575741000
D/SmartSyncScreenOnOffTimeReceiver( 4635): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4635): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4635): bNightModeTurnOffOnce = false
D/PMS     (  908): acquireWL(43a92640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{426401a0: PendingIntentRecord{42e4b1a8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1450489594426, Int=0
W/BatSI   (  908): Couldn't get kernel wake lock stats
D/PMS     (  908): releaseWL(432b5ad8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/ContextImpl( 4635): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4635): getMobilePolicyEnabled, result = true
,D/SmartSyncDataLinkTurnOffService( 4635): turnOffMobile bPolicyEnabled = true
,D/WifiStateMachine(  908): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartSyncUtils( 4635): isWifiHotSpotEnabled = false
,D/SmartSyncDataLinkTurnOffService( 4635): turnOffMobile bCheckMobileData = false
,D/LocationManagerService(  908): getProviders()=[gps, network]
,D/LocationManagerService(  908): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  908): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/SmartSyncDataLinkTurnOffService( 4635): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/PMS     (  908): releaseWL(43a92640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncUtils( 4635): isCharging status = 5
D/SmartSyncDataLinkTurnOffService( 4635): turnOffWifi ui setting = true
D/WifiStateMachine(  908): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartSyncUtils( 4635): isWifiHotSpotEnabled = false
D/SmartSyncUtils( 4635): isWifiCallingOn, bOn = false
,D/SmartSyncDataLinkTurnOffService( 4635): turnOffWifi bCheckWifiData = false
D/SmartSyncDataLinkTurnOffService( 4635): turnOffWifi bWifiConnected = true
D/LocationManagerService(  908): getProviders()=[gps, network]
,D/LocationManagerService(  908): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  908): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/SmartSyncDataLinkTurnOffService( 4635): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4635/1000)
D/SmartSyncUtils( 4635): isCharging status = 5
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): acquireWL(44066cc0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10028 null
,D/GCM     ( 1376): Message class mow
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1376/10028)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  908): handleInetConditionChange: starting a change hold
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10028)
,D/PMS     (  908): acquireWL(44066b30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10028 null
,D/PMS     (  908): releaseWL(44066cc0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  908): releaseWL(44066b30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  908): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1136): environment dirty rate=13 [137][19][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1136): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1136): nl80211: survey data missing!
E/wpa_supplicant( 1136): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1136): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(4405a640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4405a640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(440334a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1037290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(440334a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(44023100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(44023100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1611): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43b2a640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(43b2a640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1611): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43aca720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1097290, Int=0
,D/PMS     (  908): releaseWL(43aca720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43ab5350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43ab5350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43ab13e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43ab13e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43ab05d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1157290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43ab05d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43a9eee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1611): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): releaseWL(43a9eee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  353): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(423b8d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1217290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(423b8d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(420559a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(420559a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): onReceive BATTERY_CHANGED
,D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  908): updateBatteryInfo
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1611): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
D/PowerUI ( 1117): closing low battery warning: level=100
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(41f46cb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1277290, Int=0
,D/PMS     (  908): releaseWL(41f46cb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(423973d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(423973d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42114130): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1337290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42114130): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(41efa0b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(41efa0b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1611): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42458fd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42458fd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4237b338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1397290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4237b338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(41b40230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(41b40230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1611): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(41e564d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(41e564d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(425efab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1457290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(425efab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42406690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): releaseWL(42406690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  908): updateBatteryInfo
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
,D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1611): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43aec328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): releaseWL(43aec328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1611): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(425927d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1517290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(425927d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(425acd98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(425acd98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4202d748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/BatteryService(  908): n_update end
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1611): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1611): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(4202d748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42385b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1577290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42385b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43450680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43450680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42cdf780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42cdf780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4258f310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1637290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4258f310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(41e42be0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(41e42be0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4260dd50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1697290, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4260dd50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(425a32d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(425a32d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(41dbb568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1757289, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(41dbb568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): acquireWL(432b1730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(432b1730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  353): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(42584290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1817290, Int=0
,I/ProcessStatsService(  908): Prepared write state in 48ms
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
D/PMS     (  908): releaseWL(42584290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  908): Pruning old procstats: /data/system/procstats/state-2015-12-18-14-26-50.bin
,D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,D/PMS     (  908): acquireWL(424dc6e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41e3e380: PendingIntentRecord{4247fd78 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1506143, Int=0
V/AlarmManager(  908): sending alarm PendingIntent{42355c40: PendingIntentRecord{42552368 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820891, Int=1800000
,D/PMS     (  908): acquireWL(42515068): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
V/AlarmManager(  908): sending alarm PendingIntent{42356af8: PendingIntentRecord{422e85b8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450490422898, Int=900000
D/ConnectivityService(  908): Done.
,D/ConnectivityService(  908): Setting timer for 720seconds
,D/PMS     (  908): releaseWL(42515068): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/ContextImpl( 4635): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  908): releaseWL(424dc6e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): acquireWL(43b226e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43b226e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4269f938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,D/Process (  908): killProcessQuiet, pid=4349
V/AlarmManager(  908): sending alarm PendingIntent{423da2c8: PendingIntentRecord{423d9740 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1877290, Int=0
,I/ActivityManager(  908): Killing 4349:com.android.settings:remote/1000 (adj 15): empty for 1802s
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4269f938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
I/ActivityManager(  908): Recipient 4349
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4724): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4724): ====startRecUseTime====
D/htc.customization.log.level( 4724):  is 
W/CustomizationLogLevel( 4724): Level value is invalid, use default level 2
D/CustomizationManager( 4724):  Read ACC file spent 0.104 (s)
D/CIDMapFileReader( 4724): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4724): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4724): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4724): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4724): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4724): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4724): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4724): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4724): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4724): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4724): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4724): Parsing tag category name = system
I/CustomizationCIDLoader( 4724): Parsing tag category name = application
I/CustomizationCIDLoader( 4724): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4724): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4724): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4724): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4724): Parsing tag category name = Settings
D/CustomizationManager( 4724):  Read CID file spent 0.155 (s)
D/CustomizationManager( 4724):  All configurations done spent 0.155 (s)
W/HtcNativeFlag( 4724): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4724): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4724): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4724): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  908): deletePackageAsUser: pkg=com.test.thalitest, pid=4724, uid=2000 user=0
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  908): killProcessQuiet, pid=4537
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  908): Killing 4537:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
I/ActivityManager(  908): Killing 4512:com.android.chrome/u0a96 (adj 15): empty for 1802s
D/Process (  908): killProcessQuiet, pid=4512
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  908): killProcessQuiet, pid=4484
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  908): killProcessQuiet, pid=3882
I/ActivityManager(  908): Killing 4484:com.google.android.setupwizard/u0a78 (adj 15): empty for 1802s
I/ActivityManager(  908): Killing 3882:com.google.android.music:main/u0a154 (adj 15): empty for 1802s
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  908): killProcessQuiet, pid=4433
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  908): killProcessQuiet, pid=4102
I/ActivityManager(  908): Killing 4433:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1809s
I/ActivityManager(  908): Killing 4102:com.android.vending/u0a73 (adj 15): empty for 1824s
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  908): Recipient 4484
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3882
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 4512
D/MediaRouterService(  908): Client com.google.android.music (pid 3882): Died!
I/ActivityManager(  908): Recipient 4433
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 4537
I/ActivityManager(  908): Recipient 4102
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  908): Skipping PackageSetting{422548c0 com.example.hello/10356} due to missing metadata
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/dalvikvm-heap( 4138): Grow heap (frag case) to 15.195MB for 1821008-byte allocation
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1611): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1611): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
I/acms    ( 1926): Unregistering com.test.thalitest
E/acms    ( 1926): Could not unregister removed application com.test.thalitest
D/DotMatrix( 1611): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/GeofencerStateMachine( 1456): Ignoring removeGeofence because network location is disabled.
D/PMS     (  908): acquireWL(44109eb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1456 10028 null
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/Launcher( 1269): Deferring update until onResume
D/Launcher( 1269): waitUntilResume // bindAppsRemoved
D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  908): releaseWL(44109eb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/VoicemailCleanupService( 1298): Cleaning up data for package: com.test.thalitest
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
D/PackageBroadcastService( 2213): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  908): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4738 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
E/ExternalAccountType( 1335): Unsupported attribute readOnly
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/MultiDex( 4738): install
I/MultiDex( 4738): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/MultiDex( 4738): loading existing secondary dex files
I/MultiDex( 4738): load found 1 secondary dex files
I/MultiDex( 4738): install done
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  908): Delaying start of: ServiceRecord{43ab8ae8 u0 com.google.android.gms/.wearable.service.WearableControlService}
D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  908): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4756 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PeopleContactsSync( 2213): CP2 sync disabled
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2213, uid=10028, userID:0
I/ProviderInstaller( 4738): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/Icing   ( 2213): doRemovePackageData com.test.thalitest
D/PMS     (  908): acquireWL(424d7170): PARTIAL_WAKE_LOCK  Icing 0x1 2213 10028 null
D/PMS     (  908): releaseWL(424d7170): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  908): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4756): install
I/MultiDex( 4756): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4756): loading existing secondary dex files
I/MultiDex( 4756): load found 1 secondary dex files
I/MultiDex( 4756): install done
I/ProviderInstaller( 4756): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  908): Resuming delayed broadcast
E/SharedPreferencesImpl( 1208): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/[PluginManager]RegisterService( 1407): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/SQLiteLog( 1407): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1407): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5ca51a30
W/[PluginManager]RegisterService( 1407): provider may killed!
W/[PluginManager]RegisterService( 1407): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1407): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1407): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1407): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1407): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1407): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1407): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1407): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1407): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1407): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1407): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1407): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1407): handle notify Blinkfeed plugin client changed
I/ActivityManager(  908): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4776 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
D/Process (  908): killProcessQuiet, pid=4138
I/ActivityManager(  908): Killing 4138:com.google.android.apps.plus/u0a160 (adj 15): empty for 1803s
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/SQLiteDatabase( 4738): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4738): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4738): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4738): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4738): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4738): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4738): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4738): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4738): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4738): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4738): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4738): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4738): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4738): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4738): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4738): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4738): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4738): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4738): threadid=12: thread exiting with uncaught exception (group=0x41715e30)
E/ActivityManager(  908): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4738): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4738): Process: com.google.android.gms.drive, PID: 4738
E/AndroidRuntime( 4738): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4738): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4738): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4738): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4738): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4738): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4738): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4738): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4738): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4738): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4738): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4738): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4738): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4738): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4738): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4738): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4738): 	at ctn.run(SourceFile:985)
D/Process ( 4738): killProcess, pid=4738
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4738): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  908): Recipient 4138
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4776, uid=10073, userID:0
D/Finsky  ( 4776): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (4776/10073)
D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (4776/10073)
I/ActivityManager(  908): Recipient 4738
I/ActivityManager(  908): Process com.google.android.gms.drive (pid 4738) has died.
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
D/Finsky  ( 4776): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/TrimMemoryManager( 1269): [trimMemory] 5
W/Settings( 4776): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4776): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4776): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4776): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4776): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4776): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4776): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4776): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4776): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4776): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4776): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4776): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4776): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4776): threadid=25: thread exiting with uncaught exception (group=0x41715e30)
E/AndroidRuntime( 4776): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4776): Process: com.android.vending, PID: 4776
E/AndroidRuntime( 4776): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4776): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4776): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4776): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4776): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4776): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4776): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4776): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4776): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4776): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  908): App crashed! Process: com.android.vending
D/Process (  908): killProcessQuiet, pid=3817
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 3817:com.android.settings/1000 (adj 15): empty for 1802s
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
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
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4776, uid=10073, userID:0
D/Process ( 4776): killProcess, pid=4776
D/Process ( 4776): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
D/Prism.PackageStateRece_( 1269): action: android.intent.action.PACKAGE_REMOVED
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 4776
I/ActivityManager(  908): Process com.android.vending (pid 4776) has died.
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  908): Client connection lost with reason: 4
I/ActivityManager(  908): Recipient 3817
I/IcingCorporaProvider( 2895): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  908): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4811 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2895): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2895): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x64418fc0
W/dalvikvm( 2895): threadid=14: thread exiting with uncaught exception (group=0x41715e30)
E/ActivityManager(  908): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2895): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2895): Process: com.google.android.googlequicksearchbox:search, PID: 2895
E/AndroidRuntime( 2895): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2895): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2895): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2895): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2895): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2895): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2895): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2895): 	at cid.d(PG:186)
E/AndroidRuntime( 2895): 	at clo.g(PG:594)
E/AndroidRuntime( 2895): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2895): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2895): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2895): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2895): 	at clr.tL(PG:827)
E/AndroidRuntime( 2895): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2895): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2895): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2895): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2895): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2895): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2895): killProcess, pid=2895
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 2895): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  908): Recipient 2895
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.google.android.googlequicksearchbox:search (pid 2895) has died.
D/WifiService(  908): Client connection lost with reason: 4
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
D/MediaRouterService(  908): Client com.google.android.googlequicksearchbox (pid 2895): Died!
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/PackageManager(  908): Unable to load service info ResolveInfo{4254f268 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteDatabase( 4811): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4811): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4811): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4811): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4811): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4811): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4811): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4811): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4811): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4811): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4811): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4811): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4811): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4811): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4811): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4811): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4811): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4811): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4811): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4811): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4811): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4811): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4811): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4811): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4811): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4811): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4811): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4811): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4811): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4811): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4811): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4811): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4811): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4811): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4811): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4811): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4811): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4811): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4811): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4811): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4811): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4811): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4811): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4811): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4811): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4811): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4811): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4811): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4811): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4811): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4811): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4811): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4811): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4811): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4811): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4811): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4811): Opened ClientFlag.db in read-only mode
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41bd8e70 +
I/Prism.WidgetManager( 1269): onLoadItems() +
E/SQLiteDatabase( 4811): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4811): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4811): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4811): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4811): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4811): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4811): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4811): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4811): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4811): threadid=11: thread exiting with uncaught exception (group=0x41715e30)
E/ActivityManager(  908): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4811): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4811): Process: com.google.android.apps.docs, PID: 4811
E/AndroidRuntime( 4811): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4811): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4811): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4811): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4811): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4811): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4811): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4811): 	at aho.run(AbstractDatabaseInstance.java:455)
D/Process ( 4811): killProcess, pid=4811
D/Process ( 4811): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  908): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4827 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
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
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 4811
I/ActivityManager(  908): Process com.google.android.apps.docs (pid 4811) has died.

```
