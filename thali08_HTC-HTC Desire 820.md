#### Test 5065027869d93ea_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  903): acquireWL(428f3888): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
D/PMS     (  903): releaseWL(428f3888): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (1217/10028)
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (1217/10028)
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [1][0][0]
W/GLSUser ( 1362): GoogleAccountDataService.getToken()
W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/DotMatrix( 1570): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1112): com.google.android.gms (false,0)
W/CheckinRequestBuilder( 1217): awaiting user notification for token
D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{42118548 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1112): com.google.android.gms 2 10 3 12
I/CheckinTask( 1217): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
W/GoogleHttpClient( 1217): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
D/GCM     ( 1362): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  903): releaseWL(43aa37d0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1217): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41f7eee0 that was originally bound here
E/ActivityThread( 1217): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41f7eee0 that was originally bound here
E/ActivityThread( 1217): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1217): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1217): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1217): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1217): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1217): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1217): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1217): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1217): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1217): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1217): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1217): 	at bks.a(SourceFile:298)
E/ActivityThread( 1217): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1217): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1217): 	at java.lang.Thread.run(Thread.java:864)
I/GCM     ( 1362): GCM config loaded
D/CustomizationManager( 4559): ====startRecUseTime====
D/htc.customization.log.level( 4559):  is 
W/CustomizationLogLevel( 4559): Level value is invalid, use default level 2
D/CustomizationManager( 4559):  Read ACC file spent 0.075 (s)
D/CIDMapFileReader( 4559): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4559): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4559): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4559): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4559): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4559): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4559): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4559): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4559): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4559): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4559): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4559): Parsing tag category name = system
I/CustomizationCIDLoader( 4559): Parsing tag category name = application
I/CustomizationCIDLoader( 4559): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4559): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4559): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4559): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4559): Parsing tag category name = Settings
D/CustomizationManager( 4559):  Read CID file spent 0.122 (s)
D/CustomizationManager( 4559):  All configurations done spent 0.122 (s)
W/HtcNativeFlag( 4559): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4559): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4559): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4559): Fail to get flag for type 'language', use default value: -1
I/SensorManager(  903): mEventCount = 1050
W/CpuWake (  903): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  903): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4559
D/PMS     (  903): acquireHCC(44253ab8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 903 1000 null
D/PMS     (  903): acquireHCC(428337b8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 903 1000 null
I/Intent  (  903): @test_code: getHtcIntentFlag: 0 obj: 1127554120
D/PMS     (  903): acquireWL(4390e360): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 903 1000 null
I/FeedHostManager( 1263): [onPause]
I/FeedProviderManager( 1263): onPause
I/FeedHostManager( 1263): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41fb26b0
I/SocialFeedProvider( 1263): +onPause
I/SocialFeedProvider( 1263): -onPause
E/cutils-trace( 4559): Error opening trace file: No such file or directory (2)
I/ActivityManager(  903): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4571 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1263): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4571): Binding Chromium to main looper Looper (main, tid 1) {41e72698}
I/LibraryLoader( 4571): Expected native library version number "",actual native library version number ""
I/chromium( 4571): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4571): Initializing chromium process, renderers=0
D/PMS     (  903): acquireWL(42cb7c10): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  903): acquireWL(42db3e78): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  903): releaseWL(42db3e78): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  903): java.lang.Throwable: stack dump
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@433d33b0:true
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4571): 1105756368: getState(). Returning 12
I/Adreno-EGL( 4571): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4571): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4571): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4571): Local Branch: 
I/Adreno-EGL( 4571): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4571): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4571):                  aa63bbd948f41d15fc72f585e
,W/chromium( 4571): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4571): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4571): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4571): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4571): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4571): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4571): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4571): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4571): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4571): CordovaWebView is running on device made by: HTC
W/AwContents( 4571): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  903): Disable input method client, pid=1263
W/ResourceType( 4571): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4571): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41eb9780, mServedView=org.apache.cordova.engine.SystemWebView{41e7f3e8 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1203): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1203): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1203): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1203): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  903): Enable input method client, pid=4571
W/AwContents( 4571): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  903): Displayed com.test.thalitest/.MainActivity: +409ms
D/PMS     (  903): releaseWL(4390e360): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4571): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4571): JniHelper::setJavaVM(0x41a29010), pthread_self() = 1663709288
D/JX-Cordova( 4571): jxcore cordova android initializing
D/WIFI_ICON( 1112): WifiActivity: 1
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/dalvikvm-heap( 4571): Grow heap (frag case) to 11.601MB for 144892-byte allocation
,I/dalvikvm-heap( 4571): Grow heap (frag case) to 11.716MB for 217334-byte allocation
,I/dalvikvm-heap( 4571): Grow heap (frag case) to 11.893MB for 325996-byte allocation
,I/dalvikvm-heap( 4571): Grow heap (frag case) to 12.167MB for 488990-byte allocation
,I/dalvikvm-heap( 4571): Grow heap (frag case) to 12.573MB for 733480-byte allocation
,I/dalvikvm-heap( 4571): Grow heap (frag case) to 14.020MB for 1650320-byte allocation
,I/dalvikvm-heap( 4571): Grow heap (frag case) to 15.438MB for 2475476-byte allocation
,W/CpuWake (  903): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<release mCpuPerf_cpu_count wakelock
,W/CpuWake (  903): >>release mCpuPerf_Freq wakelock
W/CpuWake (  903): <<release mCpuPerf_Freq wakelock
D/PMS     (  903): releaseHCC(44253ab8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  903): releaseHCC(428337b8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4571): Grow heap (frag case) to 17.468MB for 3713210-byte allocation
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,W/jxcore-log( 4571): Initializing JXcore engine
,W/jxcore-log( 4571): JXcore engine is ready
,W/jxcore-log( 4571): Starting JXcore engine
,W/jxcore-log( 4571): Platform android
W/jxcore-log( 4571): 
,W/jxcore-log( 4571): Process ARCH arm
W/jxcore-log( 4571): 
,D/PMS     (  903): releaseWL(42cb7c10): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4571): JXcore Cordova bridge is ready!
I/jxcore-log( 4571): 
,W/jxcore-log( 4571): JXcore engine is started
,I/chromium( 4571): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/Process (  903): killProcessQuiet, pid=4329
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4329:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4329
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  903): Client connection lost with reason: 4
,D/WifiDataStallTracker(  903): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  903): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  903): updateDataStallInfo: mDataStallTxRxSum={txSum=188 rxSum=161} preTxRxSum={txSum=174 rxSum=151}
D/WifiDataStallTracker(  903): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  903): onDataStallAlarm: tag=19330 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19331 delay=15s
D/PMS     (  903): acquireWL(43a99a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{434da7b0: PendingIntentRecord{42857b88 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=102800, Int=0
D/PMS     (  903): releaseWL(43a99a00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4571): Toggling radios to true
I/jxcore-log( 4571): 
,D/BluetoothAdapter( 4571): enable(): BT is already enabled..!
,D/WifiManager( 4571): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 2
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1098
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
,W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  903): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  903): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
,W/Settings:Agent(  903): << traceCallingStack(): 0(ms)
D/WifiManager( 4571): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  903): doBoolean: DISCONNECT
D/WifiManager( 4571): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): TDLS: Tear down peers
,I/wpa_supplicant( 1163): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4571): Radios toggled
I/jxcore-log( 4571): 
,D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  903): New client listening to asynchronous messages
D/WifiService(  903): setWifiEnabled: true pid=4571, uid=10348
E/WifiService(  903): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  903): isSprintWifiRestricted(): false
I/WifiService(  903): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  903): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4571): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4571): 
I/jxcore-log( 4571): Perf Test app loaded loaded
I/jxcore-log( 4571): 
I/jxcore-log( 4571): check test folder
I/jxcore-log( 4571): 
I/jxcore-log( 4571): found test : ./testFindPeers.js
I/jxcore-log( 4571): 
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1163): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1163): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1163): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  903): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/jxcore-log( 4571): found test : ./testSendData.js
I/jxcore-log( 4571): 
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1163): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/HTCRequest(  903): WifiMonitor:getReasonFromEventString() 3
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  903): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8d3ebc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1163):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1163): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING (0)+
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1163): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1163): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  903): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv ,error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1163): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1163): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1163): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1163): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  903):    returned true
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiPerfLock(  903): release()
,D/WifiStateMachine(  903): PerfLock released for exiting ConnectedState
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): Power_Mode_Type mode = 0
I/wpa_supplicant( 1163): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  903):    returned true
,D/DhcpStateMachine(  903): [RunningState] Stop DHCP
D/ConnectivityService(  903): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  903): acquireWL(4380abd8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 903 1000 null
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  903): doBoolean: RECONNECT
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): Fast associate: Old scan results
I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  903):    returned true
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/WifiStateMachine(  903): Enter handleNetworkDisconnect
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=19331 mDataStallAlarmIntent=PendingIntent{428eece8: PendingIntentRecord{42857b88 android broadcastIntent}}
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  903): Provision feature enable=false
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  903): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): Power_Mode_Type mode = 0
I/wpa_supplicant( 1163): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
D/UsbnetStateTracker(  903): isAvailable+-
D/UsbnetStateTracker(  903): reconnect
,D/UsbnetStateTracker(  903): isAvailable+-
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  903): default: reconnect()
D/MDST    (  903): default: setTeardownRequested(false)
D/MDST    (  903): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  903): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1869/10178)
D/WifiStateMachine(  903): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WISPrService( 4461): >>>>>WISPrService start isConnected = false<<<<<
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  903): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  903): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  903): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4461): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4461): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4461): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiService(  903): New client listening to asynchronous messages
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1869/10178)
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/ConnectivityService(  903): resetConnections(wlan0, 3)
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  903): acquireWL(4274b618): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1362 10028 null
,D/ConnectivityService(  903): flush DNS cache for net 1(wlan0)
D/libc    (  364): [NET] entry_id:5   entry:0xb77d78e0  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb77d8190  removed 
D/libc    (  364): [NET] entry_id:9   entry:0xb77d8b90  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb77d8000  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb77dc1d0  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb77dc108  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb77d8328  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb77dbfd8  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb77dc410  removed 
D/libc    (  364): [NET] entry_id:10   entry:0xb77d8ce8  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  903): acquireWL(42491530): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  903): startScan Pid: 903 Uid 1000
,D/WifiNative-wlan0(  903): doBoolean: SCAN
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1163): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  903):    returned false
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  903): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/BatSI   (  903): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  903): reportInetCondition for net -1, percentage: 0 by  (1362/10028)
D/PMS     (  903): releaseWL(4274b618): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:1
I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/PMS     (  903): releaseWL(42491530): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  903): acquireWL(429178d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
D/PMS     (  903): releaseWL(429178d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  903): mActiveDefaultNetwork: -1
D/ConnectivityService(  903): handleInetConditionChange: no active default network - ignore
,I/Choreographer( 4571): Skipped 87 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4571): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  903): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4623 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  903): bSetPropertyMultiRAB:false
D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  903): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
I/Tethering(  903): ipv4Default null
I/Tethering(  903): No IPv4 upstream interface, giving up.
,D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@424d3940
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = CM36282 Light sensor
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@424d3940, eanble = 0, strlen(mName) = 59
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  903): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f45a38
W/SensorService(  903): Listener[1] = com.htc.smartdim.sensor_eye@42a91e80
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
D/CaptivePortalTracker(  903): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  903): NoActiveNetworkState
D/GpsLocationProvider(  903): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1404/10028)
I/PMS     (  903): Going to sleep due to screen timeout...
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1898/1000)
I/ActivityManager(  903): mThumbnailWidth=360, mThumbnailHeight=640
D/PMS     (  903): acquireWL(42895b00): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
W/BatSI   (  903): Couldn't get kernel wake lock stats
D/PMS     (  903): releaseWL(42895b00): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
V/LightsService(  903): setLight #2: color=#0
D/qdlights(  903): set_light_buttons_func: on=0 brightness=0
V/LightsService(  903): setLight #0: color=#0
,D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1869/10178)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4403/10100)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1263/10075)
,I/ConnectivityHelper( 1263): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,W/PMS     (  903): mWirelessDisplayManager is null
D/WirelessDisplayService(  903): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4403/10100)
,D/SurfaceControl(  903): Excessive delay in blankDisplay() while turning screen off: 370ms
D/PMS     (  903): nativeSetInteractive:false
D/PMS     (  903): nativeSetInteractive:false done
D/PMS     (  903): nativeSetAutoSuspend:true
D/PMS     (  903): nativeSetAutoSuspend:true done
D/HABCtrl (  903): TPE algorithm. remove timeout.
I/InputManager(  903): Cancel all due to getting PMS screen off broadcast
D/PMS     (  903): OOBE c monitor 11
I/IntentController( 1112): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1251): ScreenObserver: OFF
D/NfcService( 1251): applyRouting - 0
,V/KeyguardServiceDelegate(  903): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@44302908)
I/InputMethodManagerService(  903): screenObserver, isScreenOn=false
I/InputMethodManagerService(  903): Disable input method client, pid=4571
D/PMN     (  903): wakingUp
,W/ResourceType( 4571): No package identifier when getting name for resource number 0x00000064
D/NfcService( 1251): applyRouting -2
,I/InputMethodManager( 4571): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41e7f3e8 VFEDH.C. .F...... 0,0-720,1134 #64}
,V/KeyguardServiceDelegate(  903): **** SHOWN CALLED ****
D/PMS     (  903): acquireWL(42d0f720): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1251 1027 null
D/PMS     (  903): releaseWL(42d0f720): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  903): acquireWL(43b44d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/AlarmManager(  903): ACTION_SCREEN_ON
I/AlarmManager(  903): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done recovering
I/BatteryService(  903): n_update end
I/AlarmManager(  903): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done EPS screen off alarm recovering
,D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  903): doBoolean: SET pno 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): SET_SCREEN_ON:On
I/wpa_supplicant( 1163): htc_wext_set_keepalive +
I/wpa_supplicant( 1163): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1163): getPrivFuncNum +	
I/wpa_supplicant( 1163): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  903):    returned true
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): CTRL_IFACE SET 'pno'='0'
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/WifiNative-wlan0(  903):    returned true
I/WindowManager(  903): No lock screen! windowToken=null
D/PMS     (  903): releaseWL(43b44d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  903): onScreenOn
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WirelessDisplayService(  903): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,D/MtpService( 2741): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1251): applyRouting - 0
,D/MtpService( 2741): [MTP][onReceive]-
,D/NfcService( 1251): applyRouting -2
I/HtcPowerSaver(  903): << updateStatus
D/PMS     (  903): acquireWL(42a87f10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1251 1027 null
D/PMS     (  903): releaseWL(42a87f10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/ClockThread( 1112): stop update clock
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
D/NetworkPolicy(  903): updateScreenOn: false
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/MusicStore( 4623): Database version: 95
,W/ContextImpl( 4623): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/ContextImpl( 4623): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1823): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1823): onScreenOn: 1450484608088
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1823): onScreenOn: 1450484608088
D/PMS     (  903): acquireWL(42832a68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1404 10028 null
,D/PMS     (  903): releaseWL(42832a68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f45a38
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f45a38, eanble = 0, strlen(mName) = 91
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  903): Listener[0] = com.htc.smartdim.sensor_eye@42a91e80
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMN     (  903): goingToSleep
D/PMS     (  903): acquireWL(4393ae40): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 903 1000 null
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/AlarmManager(  903): ACTION_SCREEN_OFF
I/AlarmManager(  903): [AlarmQueuing] screen off now: 
I/AlarmManager(  903): [AlarmQueuing] data connection: true
,I/AlarmManager(  903): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=19332 mDataStallAlarmIntent=null
,W/ContextImpl( 4623): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/WifiNative-wlan0(  903): doBoolean: SET pno 1
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): CTRL_IFACE SET 'pno'='1'
D/PMS     (  903): releaseWL(4393ae40): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/PMS     (  903): acquireWL(4326c8f8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 903 1000 null
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1163): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-47
D/wpa_supplicant( 1163): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=8 entropy=0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
,W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available,
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-47
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 3,
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 1
,I/wpa_supplicant( 1163): wpa_s->is_screen_on 1
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): selected network = 1
D/wpa_supplicant( 1163): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8d404e8  current_ssid=0x0
D/wpa_supplicant( 1163): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): supplicant attached completed, trigger assoc.
,D/wpa_supplicant( 1163): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1163): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1163): check if in concurrent case
I/wpa_supplicant( 1163): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiNative-wlan0(  903):    returned true
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1163): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1163): wpa_supplicant_associate, 1780
,D/wpa_supplicant( 1163): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1163): RSN: PMKSA cache search - network_ctx=0xb8d404e8 try_opportunistic=0
D/wpa_supplicant( 1163): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1163): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1163): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1163): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
,D/wpa_supplicant( 1163): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1163): nl80211: Unsubscribe mgmt frames handle 0xb8d3f718 (mode change)
D/wpa_supplicant( 1163): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8d3f718
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 1
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1163):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1163):   * freq=2412
D/wpa_supplicant( 1163):   * Auth Type 0
D/wpa_supplicant( 1163):   * WPA Versions 0x2
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1163): nl80211: Connect request send successfully
D/wpa_supplicant( 1163): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1163): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): SET_SCREEN_ON:Off
I/wpa_supplicant( 1163): htc_wext_set_keepalive +
I/wpa_supplicant( 1163): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1163): getPrivFuncNum +	
I/wpa_supplicant( 1163): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive fnum = 0x8bf6
,I/wpa_supplicant( 1163): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1163): get_ip_address source addr = 02000000
I/wpa_supplicant( 1163): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1163): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  903):    returned true
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SET pno 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): CTRL_IFACE SET 'pno'='1'
D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
,V/SRS_Proc(  371): ParamSet string: screen_state=off
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(4326c8f8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=1 len=6
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (665) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-59
I/wpa_supplicant( 1163): tsf=0000000021401154
,I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=1
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000105078999
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=2
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2427
I/wpa_supplicant( 1163): level=-73
I/wpa_supplicant( 1163): tsf=0000000021401161
,I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=3
I/wpa_supplicant( 1163): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-78
I/wpa_supplicant( 1163): tsf=0000000021401165
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1163): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=4
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-86
I/wpa_supplicant( 1163): tsf=0000000021401177
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/ContactMessageStore( 1237): start background delete task...
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 5220, timestamp: 21401154, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 2412, timestamp: 105078999, distance: ?(cm), distanceSd: ?(cm)
D/NetworkPolicy(  903): updateScreenOn: false
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 21401161, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -78, frequency: 2437, timestamp: 21401165, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 21401177, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 5 to mScanResults
,D/BatSI   (  903): WIFI scan stopped for: 440a0300 uid:1000
D/ContactMessageStore( 1237): size: 0 , 0
D/ContactMessageStore( 1237): Background delete complete
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (5) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4623): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4623): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4623, uid=10154, userID:0
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,D/MediaRouterService(  903): Client com.google.android.music (pid 4623): Registered
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,I/MediaRouter( 4623): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] getTotalRam: 1873 Mb
D/PMS     (  903): acquireWL(44314ac0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1404 10028 null
,D/PMS     (  903): releaseWL(44314ac0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1823): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1823): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1823): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1823): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1823): onScreenOff
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.music (4623/10154)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (2741/10021)
,D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1163): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1163): nl80211: Connect event
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1163): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1163): Add randomness: count=9 entropy=1
I/wpa_supplicant( 1163): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1163): TDLS: Remove peers on association
D/wpa_supplicant( 1163): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1163): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1163): EAPOL: enable timer tick
D/wpa_supplicant( 1163): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1163): htc_wext_set_keepalive +
I/wpa_supplicant( 1163): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1163): getPrivFuncNum +	
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1163): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1163): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1163): Get randomness: len=32 entropy=2
D/WifiMonitor(  903): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  903): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  903): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  903): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantSta,teChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
I/ActivityManager(  903): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4652 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
D/Tethering(  903): interfaceStatusChanged wlan0, true
D/Tethering(  903): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1163): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiStateMachine(  903): Enter handleAssociatedWithEvent
D/WifiStateMachine(  903): Associated
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8d3f9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1163):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1163): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6efdb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1163):    broadcast key
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 11
D/WifiStateMachine(  903): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  903): Exit handleAssociatedWithEvent
I/wpa_supplicant( 1163): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1163): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1163): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1163): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiStateMachine(  903): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  903): updateConnectedAP...
E/wpa_supplicant( 1163): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1163): set send_ind_to_ndc = 0
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1163): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1163): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1163): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1163): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1163): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1163): EAPOL authentication completed successfully
I/wpa_supplicant( 1163): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 79
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
D/Tethering(  903): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  903): This record is existed, only update it...
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/MediaRouter( 4623): getSelectedRoute
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (4623/10154)
I/NetworkMonitor( 4623): type=WIFI subType= reason=null isConnected=false
D/WifiStateMachine(  903): fetchFrequency(), freq = 2412
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  903): This record is existed, only update it...
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): mActiveDefaultNetwork: -1
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/WISPrService( 4461): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4461): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiNative-wlan0(  903): doBoolean: SET pno 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1163): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  903):    returned true
D/DhcpStateMachine(  903): [StoppedState] Start DHCP
D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  903):    returned true
D/Process (  903): killProcessQuiet, pid=4352
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): Power_Mode_Type mode = 1
I/wpa_supplicant( 1163): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 61
D/ACRA    ( 4652): ACRA is enabled for com.facebook.katana, intializing...
D/WifiNative-wlan0(  903):    returned true
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1163): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  903):    returned null
E/WifiStateMachine(  903): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  903):    returned null
D/WifiStateMachine(  903): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  903): acquireWL(43e6ffa8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 903 1000 null
D/WifiStateMachine(  903): handlePreDhcpSetup mBluetoothConnectionActive: false
I/ActivityManager(  903): Killing 4352:com.htc.mediamanager/u0a32 (adj 15): empty #17
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4623, uid=10154, userID:0
D/WifiP2pService(  903): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41f43980 target=com.android.internal.util.StateMachine$SmHandler }
,D/ACRA    ( 4652): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4652): Looking for error files in /data/data/com.facebook.katana/app_minidumps
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41f43980 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:0
,W/SystemClassLoaderAdder( 4652): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4652): Preparing secondary program dexes.
V/DexLibLoader( 4652): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4652): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4652): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4652): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4652): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4652): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
,V/DexLibLoader( 4652): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4652): Dex already copied
D/OdexVerifier( 4652): Odex verification is skipped.
,V/DexLibLoader( 4652): Creating class loader
,V/DexLibLoader( 4652): Finished creating class loader
V/DexLibLoader( 4652): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4652): Dex already copied
D/OdexVerifier( 4652): Odex verification is skipped.
,V/DexLibLoader( 4652): Creating class loader
,V/DexLibLoader( 4652): Finished creating class loader
V/DexLibLoader( 4652): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4652): Dex already copied
D/OdexVerifier( 4652): Odex verification is skipped.
,V/DexLibLoader( 4652): Creating class loader
,V/DexLibLoader( 4652): Finished creating class loader
V/DexLibLoader( 4652): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 4652): Dex already copied
D/OdexVerifier( 4652): Odex verification is skipped.
,V/DexLibLoader( 4652): Creating class loader
,V/DexLibLoader( 4652): Finished creating class loader
,V/DexLibLoader( 4652): Verifying classes from secondary dexes.
,D/DexLibLoader( 4652): DexLibLoader.ensureDexLoaded took 29 ms
,I/ActivityManager(  903): Recipient 4352
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4652): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4652): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4652): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4652): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4652): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4652): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4652): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1163): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1163): EAPOL: disable timer tick
,W/dalvikvm( 4652): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4652): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4652): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4652): Verify
,D/WifiService(  903): New client listening to asynchronous messages
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4652): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4652): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,I/dalvikvm-heap( 4652): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  903): killProcessQuiet, pid=4264,
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 4264:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,D/PMS     (  903): acquireWL(43800c00): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1217 10028 null
I/ActivityManager(  903): Recipient 4264
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(43b559c8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1217 10028 null
,D/PMS     (  903): releaseWL(43800c00): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
,D/GCM     ( 1362): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
,D/PMS     (  903): releaseWL(43b559c8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,W/fb4a(:<default>):UserScope( 4652): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4652): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/AutoSetting( 1429): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1429/10053)
W/fb4a(:<default>):UserScope( 4652): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  903): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4704 uid=10078 gids={50078, 3003, 5012}
,D/AutoSetting( 1429): Util - no network available!
,D/AutoSetting( 1429): service - onCreate()
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1429/10053)
D/AutoSetting( 1429): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1429): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  903): request 42701d40 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  903): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1429): service - mHandler: cancel location update
,D/AutoSetting( 1429): service -           changes count: 0
,D/MobileConnectivityChangeReceiver( 4704): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4704): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4704): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4704): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  903): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4720 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4704/10078)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4704/10078)
E/dalvikvm( 4652): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4652): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4704/10078)
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1163): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,I/dalvikvm-heap( 4652): Grow heap (frag case) to 9.956MB for 84664-byte allocation
E/dalvikvm( 4652): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4652): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4652): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4652): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4652): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4652): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4652): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4652): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4652): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  903): releaseWL(43e6ffa8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
D/WIFI_ICON( 1112): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiStateMachine(  903): gateway: /192.168.1.1
D/WifiNative-wlan0(  903): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1163): htc_wext_set_keepalive +
I/wpa_supplicant( 1163): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1163): getPrivFuncNum +	
I/wpa_supplicant( 1163): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1163): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1163): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1163): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  903): VerifyingLinkState enter
D/WifiStateMachine(  903): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  903): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  903): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -48, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,I/dalvikvm-heap( 4652): Grow heap (frag case) to 9.971MB for 28144-byte allocation
W/dalvikvm( 4652): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4652): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4652): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4652): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4652): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4652): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4652): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/ActivityManager(  903): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4733 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,I/ActivityManager(  903): Killing 4403:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  903): killProcessQuiet, pid=4403
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
V/NetworkPolicy(  903): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED connected
,D/WifiWatchdogStateMachine(  903): WAN detection
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/ConnectivityService(  903): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  903): default: teardown()
D/MDST    (  903): default: setTeardownRequested(true)
D/MDST    (  903): default: setEnableApn apnType =default , enable=false
D/MDST    (  903): default: setTeardownRequested(true)
D/ConnectivityService(  903): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
I/ActivityManager(  903): Recipient 4403
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,I/dalvikvm-heap( 4652): Grow heap (frag case) to 10.011MB for 39954-byte allocation
,D/WISPrService( 4461): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=100 [1][1][0]
E/ConnectivityService(  903): Unexpected mtu value: android.net.wifi.WifiStateTracker@4275da60
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/ConnectivityService(  903): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateMachine(  903): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WifiStateMachine(  903): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  903): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  903): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  903): handleConnectivityChange: resetting
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  903): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  903): acquireWL(4436ed30): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4704/10078)
D/WirelessDisplayService(  903): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  903):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(4430bc50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1217 10028 null
I/dalvikvm-heap( 4652): Grow heap (frag case) to 10.087MB for 79892-byte allocation
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/QuickSettingWifi( 1112): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,W/ContextImpl( 4733): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4733): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/PMS     (  903): acquireWL(42ef4438): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1217 10028 null
D/PMS     (  903): releaseWL(4430bc50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,W/GAV2    ( 4733): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,W/ContextImpl( 4733): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4733): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/PMS     (  903): releaseWL(42ef4438): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/ConnectivityService(  903): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  903): releaseWL(4436ed30): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,I/dalvikvm-heap( 4652): Grow heap (frag case) to 10.275MB for 75760-byte allocation
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4733/10151)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,V/WebViewChromiumFactoryProvider( 4733): Binding Chromium to main looper Looper (main, tid 1) {41e6b558}
,I/LibraryLoader( 4733): Expected native library version number "",actual native library version number ""
,I/chromium( 4733): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4733): Initializing chromium process, renderers=0
W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43caac98 u0 ReceiverList{43c9b6d8 4652 com.facebook.katana/10026/u0 remote:43c9b5b0}}
W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43caac98 u0 ReceiverList{43c9b6d8 4652 com.facebook.katana/10026/u0 remote:43c9b5b0}}
W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43d488a0 u0 ReceiverList{43d48840 4652 com.facebook.katana/10026/u0 remote:43d1db70}}
D/PMS     (  903): acquireWL(442a5f58): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  903): acquireWL(43adb548): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4733): BLUETOOTH permission is missing!
D/PMS     (  903): releaseWL(442a5f58): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4733): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4733): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4733): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4733): Local Branch: 
I/Adreno-EGL( 4733): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4733): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4733):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/PMS     (  903): acquireWL(429ab648): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1404 10028 null
,I/NSApplication( 4733): Starting up...
D/PMS     (  903): releaseWL(429ab648): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4733/10151)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4733/10151)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4107/10160)
,D/Process (  903): killProcessQuiet, pid=4422
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4107/10160)
I/ActivityManager(  903): Killing 4422:com.htc.backup/1000 (adj 15): empty #17
,D/GCoreFlp( 1404): Unknown pending intent to remove.
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1869/10178)
D/PMS     (  903): acquireWL(44300870): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1404 10028 null
D/PMS     (  903): releaseWL(44300870): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
I/ActivityManager(  903): Recipient 4422
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4788 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4652): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4652): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4652): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4788): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4788): isEpsOn(), nState = 0
D/PMS     (  903): acquireWL(43c9c818): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4788 1000 null
,D/PMS     (  903): releaseWL(43c9c818): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4788): getMobilePolicyEnabled, result = true
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  903): killProcessQuiet, pid=4446
,D/AutoSetting( 1429): receiver - intent: android.intent.action.USER_PRESENT
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4446:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/AutoSetting( 1429): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 4446
,D/TetherSettings( 4461): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4461): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4461): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 4461): Cust_ConnectToPC   : spcsc>false
D/        ( 4461): Cust_ConnectToPC   : IPT>true
,D/        ( 4461): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4461): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4461): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4461): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4461): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4461): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 4461): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 4461): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4461):  defaultType:0
W/ContextImpl( 4461): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4788): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4788): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4788): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4788): isEpsOn(), nState = 0
D/WifiService(  903): New client listening to asynchronous messages
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42a91e80
,W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 1
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42a91e80, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 0
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42a91e80, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42a91e80
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1869/10178)
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread(  903): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42a923c8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42a923c8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  903): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  903): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  903): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  903): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  903): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  903): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  903): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  903): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  903): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  903): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  903): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  903): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  903): 	at dalvik.system.NativeStart.main(Native Method)
,D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1869/10178)
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  903): releaseWL(4380abd8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  903): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,V/Tethering(  903): bSetPropertyMultiRAB:false
D/CaptivePortalTracker(  903): NoActiveNetworkState
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [2][0][0]
,D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1404/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1869/10178)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1263/10075)
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  903): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  903): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  903): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  903): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  903): Found interface wlan0
D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1263): [onReceive] WIFI(1): CONNECTED
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,I/acms    ( 1898): Checking Certificates
,I/acms    ( 1898): Checking Developer Certificates
I/acms    ( 1898): Checking Application Certificates
I/acms    ( 1898): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1898/1000)
D/PMS     (  903): acquireWL(4384d7b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(4290a408): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,I/acms    ( 1898): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1898): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1898): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1898): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
,I/acms    ( 1898): Updating next query delay: 75600000
I/mlserverapp( 1898): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1898): cancelACMSProgrammedChecks
,I/NetworkMonitor( 4623): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  903): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4704/10078)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.musicenhancer (3923/10051)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (4623/10154)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): releaseWL(4290a408): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(4384d7b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by  (2741/10021)
,D/PMS     (  903): acquireWL(4316a2b8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1217 10028 null
,D/PMS     (  903): acquireWL(429090f0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1217 10028 null
,D/PMS     (  903): releaseWL(4316a2b8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
,D/GCM     ( 1362): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/libc    ( 1362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1362): [NET] getaddrinfo-,err=8
D/libc    ( 1362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1362): [NET] getaddrinfo-, 1
,D/libc    ( 1362): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =129f +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  903): acquireWL(43753be8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1362 10028 null
D/PMS     (  903): releaseWL(429090f0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
,D/AutoSetting( 1429): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE,
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1429/10053)
D/MobileConnectivityChangeReceiver( 4704): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4704): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1429): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 217
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1362): [NET] getaddrinfo_proxy-, success
,D/AutoSetting( 1429): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4733/10151)
,D/AutoSetting( 1429): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1429): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1429/10053)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4107/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4107/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1869/10178)
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/dalvikvm-heap( 4107): Grow heap (frag case) to 13.618MB for 1821008-byte allocation
,D/AutoSetting( 1501): service - handleMessage() stop self
,D/AutoSetting( 1501): service - onDestroy() END
,D/AutoSetting( 1501): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=4478
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4478:com.htc.calendar/u0a13 (adj 15): empty #17
,D/libc    ( 1362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1362): [NET] getaddrinfo-,err=8
I/ActivityManager(  903): Recipient 4478
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/PMS     (  903): acquireWL(43cdb0c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
D/PMS     (  903): releaseWL(43cdb0c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/dalvikvm( 4571): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4571): threadid=1: thread exiting with uncaught exception (group=0x41a3ae30)
,E/ActivityManager(  903): App crashed! Process: com.test.thalitest,
E/AndroidRuntime( 4571): FATAL EXCEPTION: main
E/AndroidRuntime( 4571): Process: com.test.thalitest, PID: 4571
E/AndroidRuntime( 4571): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4571): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4571): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4571): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4571): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4571): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4571): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4571): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4571): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4571): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4571): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4571): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4571): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4571): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4571): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4571): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4571): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4571): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4571): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  903):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  903): killProcessQuiet, pid=4493
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,D/Process ( 4571): killProcess, pid=4571
,I/ActivityManager(  903): Killing 4493:com.android.settings:remote/1000 (adj 15): empty #17
D/Process ( 4571): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  903): Recipient 4493
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GCM     ( 1362): Connected,
D/PMS     (  903): acquireWL(43b42630): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1362 10028 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/PMS     (  903): releaseWL(43753be8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1362/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
,W/InputDispatcher(  903): channel '428eb6c8 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
D/PMS     (  903): releaseWL(43b42630): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  903): acquireWL(43256e58): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1362 10028 null
,E/InputDispatcher(  903): channel '428eb6c8 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  903): Attempted to unregister already unregistered input channel '428eb6c8 com.test.thalitest.MainActivity (s)'
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 4571
I/ActivityManager(  903): Process com.test.thalitest (pid 4571) has died.
D/WifiService(  903): Client connection lost with reason: 4
I/WindowManager(  903): WINDOW DIED Window{428eb6c8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/WindowManager(  903): Failed looking up window
W/WindowManager(  903): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@442dcdd0 does not exist
W/WindowManager(  903): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  903): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  903): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  903): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  903): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  903): WIN DEATH: null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
,D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1362/10028)
,D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
,D/GCM     ( 1362): Message class mpf
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1362/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
,D/PMS     (  903): releaseWL(43256e58): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  903): acquireWL(41f10788): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null,
,W/InputMethodManagerService(  903): Got RemoteException sending setActive(false) notification to pid 4571 uid 10348
,W/Binder  ( 1203): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1203): java.lang.NullPointerException
W/Binder  ( 1203): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1203): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1203): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1203): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  903): releaseWL(41f10788): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [7][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8990 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  903): Find DNS Address www.htc.com/23.59.123.86
,D/PMS     (  903): acquireWL(429a9dc8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4623 10154 null
,W/ContextImpl( 4623): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/PMS     (  903): releaseWL(43adb548): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/ContextImpl( 4623): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4623, uid=10154, userID:0
,I/MusicLeanback( 4623): Conditions not met for autocaching.
,I/MusicLeanback( 4623): Stop autocaching.
D/PMS     (  903): releaseWL(429a9dc8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,W/fb4a(:<default>):UserScope( 4652): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4652): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4652): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/WifiStateMachine(  903): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,I/GAV2    ( 4733): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  903): acquireWL(439b21c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1404 10028 null
,D/PMS     (  903): acquireWL(426d7b60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1404 10028 null
,D/PMS     (  903): releaseWL(439b21c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  903): releaseWL(426d7b60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/ContactMessageStore( 1237): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1237): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1429): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1429): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1429): service - requestNLP() NetworkLocationProvider not enabled
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  903): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{43a004b0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(43282970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/PMS     (  903): releaseWL(43282970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): Checking...
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43261338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43261338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(4326e1e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=136958, Int=0
,D/PMS     (  903): releaseWL(4326e1e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1429): service - has update message, not stop
,D/AutoSetting( 1429): service - mHandler: update timezone
,D/AutoSetting( 1501): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1501): service - onCreate()
,D/AutoSetting( 1501): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1501): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1570): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1501): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1501): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1501): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1501): service - mHandler: update timezone
,D/AutoSetting( 1501): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1501): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1501): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1501): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1570): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1112): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41ed8da0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.htc.htclocationservice 3 7 2 11
,D/PMS     (  903): acquireWL(429cecc8): PARTIAL_WAKE_LOCK  Icing 0x1 1217 10028 null
,D/PMS     (  903): releaseWL(429cecc8): PARTIAL_WAKE_LOCK  Icing 0x1 null,
,D/PMS     (  903): acquireWL(42d1a030): PARTIAL_WAKE_LOCK  Icing 0x1 1217 10028 null
,D/PMS     (  903): releaseWL(42d1a030): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(443292d0): PARTIAL_WAKE_LOCK  Icing 0x1 1217 10028 null
,D/PMS     (  903): releaseWL(443292d0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(427ec1f0): PARTIAL_WAKE_LOCK  Icing 0x1 1217 10028 null
,D/PMS     (  903): releaseWL(427ec1f0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(429ff328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10028}
,V/AlarmManager(  903): sending alarm PendingIntent{429a1318: PendingIntentRecord{42862628 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135188, Int=0
V/AlarmManager(  903): sending alarm PendingIntent{42344f70: PendingIntentRecord{427a4fc0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140746, Int=0
,D/GpsLocationProvider(  903): ALARM_XTRA_TIMEOUT
V/AlarmManager(  903): sending alarm PendingIntent{4269c068: PendingIntentRecord{442f03a0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450484631231, Int=563223000
D/PMS     (  903): acquireWL(43e3a060): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/PMS     (  903): acquireWL(42ef4690): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
D/PMS     (  903): acquireWL(434640e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1217 10028 null
,D/PMS     (  903): releaseWL(429ff328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  903): acquireWL(43eb94a0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1217 10028 null
,D/PMS     (  903): releaseWL(434640e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/PMS     (  903): releaseWL(42ef4690): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
,I/CheckinService( 1217): Preparing to send checkin request
,I/EventLogService( 1217): Accumulating logs since 1450484599163
,I/GoogleHttpClient( 1217): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1217): Using GMS GoogleHttpClient
D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  903): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =fcf9 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (1217/10028)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (1217/10028)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=15 [13][2][0]
,W/GLSUser ( 1362): GoogleAccountDataService.getToken()
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1570): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1217): awaiting user notification for token
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{42227368 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.google.android.gms 1 11 3 12
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=243
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
I/global  (  903): call createSocket() return a new socket.
D/libc    (  903): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  903): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  903): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  903): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  903):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (4536/10028)
,I/Adreno-EGL( 4536): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4536): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4536): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4536): Local Branch: 
I/Adreno-EGL( 4536): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4536): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4536):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4536): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4536): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4536): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4536): Local Branch: 
I/Adreno-EGL( 4536): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4536): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4536):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4536): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4536): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4536): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4536): Local Branch: 
I/Adreno-EGL( 4536): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4536): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4536):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4536): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinTask( 1217): Sending checkin request (8963 bytes)
D/libc    ( 1217): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1217): [NET] getaddrinfo-,err=8
D/libc    ( 1217): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1217): [NET] getaddrinfo-, 1
,D/libc    ( 1217): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =6570 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 50
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1217): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1217): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1217): [NET] getaddrinfo-,err=8
,D/PMS     (  903): acquireWL(43a774d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
,D/PMS     (  903): releaseWL(43a774d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (1217/10028)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=16 [42][7][0]
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (1217/10028)
,W/GLSUser ( 1362): GoogleAccountDataService.getToken()
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1570): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1217): awaiting user notification for token
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{4223ece8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.google.android.gms 1 9 3 12
,I/CheckinTask( 1217): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1217): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  903): releaseWL(43eb94a0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 1217): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@42091dc8 that was originally bound here
E/ActivityThread( 1217): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@42091dc8 that was originally bound here
E/ActivityThread( 1217): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1217): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1217): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1217): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1217): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1217): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1217): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1217): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1217): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1217): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1217): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1217): 	at bks.a(SourceFile:298)
E/ActivityThread( 1217): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1217): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1217): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1362): GCM config loaded
,D/PMS     (  903): releaseWL(43e3a060): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{43e1ece8 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1429): service - handleMessage() stop self
,D/AutoSetting( 1429): service - handleMessage() quit looper
,D/AutoSetting( 1429): service - onDestroy() END
,D/PMS     (  903): acquireWL(43f68468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,D/AutoSetting( 1501): service - handleMessage() stop self
V/AlarmManager(  903): sending alarm PendingIntent{423313e0: PendingIntentRecord{42a967d0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=168455, Int=0
,D/PMS     (  903): releaseWL(43f68468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/AutoSetting( 1501): service - onDestroy() END
,D/AutoSetting( 1501): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=3923
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3923:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3923
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(4368bc10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(4368bc10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1237): switchBindHtcMsgCursor: null
,D/PMS     (  903): acquireWL(43973d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43973d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(43cd29a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=196958, Int=0
,D/PMS     (  903): releaseWL(43cd29a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
,D/PMS     (  903): acquireWL(4394ddc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(4394ddc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(43c4e578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(43c4e578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(428ef798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=256958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(428ef798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(43b43de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43b43de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42d32d30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=316958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42d32d30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(42ecd590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(42ecd590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/GLSUser ( 1362): GoogleAccountDataService.getToken()
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1570): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,W/GLSActivity( 1362): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1362): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1362): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1362): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1362): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1362): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1362): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1362): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{4227c938 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4071): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4071): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4071): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4071): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4071): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4071): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4071): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4071): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1112): com.google.android.gms 1 12 3 12
,D/libc    ( 4071): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4071): [NET] getaddrinfo-,err=8
D/libc    ( 4071): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4071): [NET] getaddrinfo-, 1
,D/libc    ( 4071): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =4c4 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 10
D/libc    (  364): [NET]res_nsend:resplen=87
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4071): [NET] getaddrinfo_proxy-, success
I/global  ( 4071): call createSocket() return a new socket.
D/libc    ( 4071): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4071): [NET] getaddrinfo-, SUCCESS,
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/libc    ( 4071): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4071): [NET] getaddrinfo-,err=8
,D/PMS     (  903): acquireWL(43bf02f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(43bf02f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  903): acquireWL(43a5d510): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=376958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  903): releaseWL(43a5d510): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(43c91888): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43c91888): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(43cc2fe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43cc2fe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43b02cd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=436958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43b02cd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(43938c50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(43938c50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(42a5e568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42a5e568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  903): acquireWL(43d20fd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=496958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43d20fd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(42cb5de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42cb5de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(437fd798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(437fd798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42efd2c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=556958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42efd2c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=1 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1163): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1163): nl80211: Disconnect event
I/wpa_supplicant( 1163): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1163): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  903): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  903): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  903): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  903): Enter handleNetworkDisconnect
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1163): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1163): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8d3ebc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1163):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1163): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1163): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1163): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=0
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): Power_Mode_Type mode = 0
I/wpa_supplicant( 1163): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 61
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiP2pService(  903): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  903):    returned true
,D/WifiP2pService(  903): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/Tethering(  903): [isWifi] getHotspotEnabled: false
,D/DhcpStateMachine(  903): [RunningState] Stop DHCP
D/WifiStateMachine(  903): Exit handleNetworkDisconnect
D/WifiPerfLock(  903): release()
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=19333 mDataStallAlarmIntent=null
,D/WifiStateMachine(  903): PerfLock released for exiting ConnectedState
D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): Power_Mode_Type mode = 0
I/wpa_supplicant( 1163): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 61
,D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/ConnectivityService(  903): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  903): Provision feature enable=false
D/PMS     (  903): acquireWL(43cebd60): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 903 1000 null
D/ConnectivityService(  903): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  903):    returned true
D/UsbnetStateTracker(  903): isAvailable+-
D/UsbnetStateTracker(  903): reconnect
,D/UsbnetStateTracker(  903): isAvailable+-
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  903): default: reconnect()
D/MDST    (  903): default: setTeardownRequested(false)
D/MDST    (  903): default: setEnableApn apnType =default , enable=true
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  903): doBoolean: SET pno 1
D/WISPrService( 4461): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): CTRL_IFACE SET 'pno'='1'
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WISPrService( 4461): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1869/10178)
D/ConnectivityService(  903): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  903): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '53 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 53 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
,D/ConnectivityService(  903): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1163): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
,D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '54 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 54 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1869/10178)
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4461): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 4461): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] entry_id:1   entry:0xb77dc410  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb77dc1f0  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb77d7f98  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb77dc0e8  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb77d8170  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '55 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 55 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/ConnectivityService(  903): resetConnections(wlan0, 3)
D/PMS     (  903): acquireWL(43cb5708): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1362 10028 null
D/ConnectivityService(  903): flush DNS cache for net 1(wlan0)
D/PMS     (  903): acquireWL(42ddac20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  903): acquireWL(43f258a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
D/PMS     (  903): releaseWL(42ddac20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  903): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4704/10078)
D/ConnectivityService(  903): reportInetCondition for net -1, percentage: 0 by  (1362/10028)
D/PMS     (  903): releaseWL(43cb5708): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiStateMachine(  903): startScan Pid: 903 Uid 1000
I//system/bin/ip(  364): RTNETLINK answers: No such process
D/WifiNative-wlan0(  903): doBoolean: SET pno 0
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/wpa_supplicant( 1163): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1163): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1163): wpa_supplicant_scan enter
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: SCAN
I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1163): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1163): Failed to initiate AP scan
,I/wpa_supplicant( 1163): Failed to initiate AP scan, Failed_to_scan_counter:1
,D/WifiNative-wlan0(  903):    returned true
D/BatSI   (  903): WIFI scan started for: 450a0300 uid:1000
D/PMS     (  903): releaseWL(43f258a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  903): mActiveDefaultNetwork: -1
,D/ConnectivityService(  903): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (4623/10154)
,D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  903): bSetPropertyMultiRAB:false
D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
I/NetworkMonitor( 4623): type=WIFI subType= reason=null isConnected=false
D/GpsLocationProvider(  903): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  903): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  903): ipv4Default null
I/Tethering(  903): No IPv4 upstream interface, giving up.
,D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
I/ConnectivityHelper( 1263): [onReceive] WIFI(1): DISCONNECTED
D/CaptivePortalTracker(  903): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(442d9590): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/PMS     (  903): releaseWL(442d9590): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1404/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1263/10075)
,D/CaptivePortalTracker(  903): NoActiveNetworkState
I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1163): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1163): Failed to initiate AP scan
,I/wpa_supplicant( 1163): Failed to initiate AP scan, Failed_to_scan_counter:2
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1869/10178)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1898/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4704/10078)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (2741/10021)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/PMS     (  903): acquireWL(4427fa40): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1217 10028 null
,D/PMS     (  903): acquireWL(43c603e8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1217 10028 null
,D/PMS     (  903): releaseWL(4427fa40): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
,D/GCM     ( 1362): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
,D/PMS     (  903): releaseWL(43c603e8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
,D/AutoSetting( 1429): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4704): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4704): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1429/10053)
,D/AutoSetting( 1429): Util - no network available!
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1429/10053)
,D/AutoSetting( 1429): service - onCreate()
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4733/10151)
D/AutoSetting( 1429): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1429): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  903): request 42701d40 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  903): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1429): service - mHandler: cancel location update
,D/AutoSetting( 1429): service -           changes count: 0
,I/dalvikvm-heap( 4107): Grow heap (frag case) to 15.312MB for 1821008-byte allocation
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4107/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4107/10160)
,D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1869/10178)
,D/GCM     ( 1362): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/dalvikvm-heap( 4107): Grow heap (frag case) to 17.052MB for 1821008-byte allocation
,I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1163): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1163): Failed to initiate AP scan
,I/wpa_supplicant( 1163): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-59
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1163): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-76
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
D/wpa_supplicant( 1163): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=10 entropy=0
D/wpa_supplicant( 1163): Add randomness: count=11 entropy=1
D/wpa_supplicant( 1163): Add randomness: count=12 entropy=2
D/wpa_supplicant( 1163): Add randomness: count=13 entropy=3
D/wpa_supplicant( 1163): Add randomness: count=14 entropy=4
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1163): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): No APs found - clear blacklist and try again
E/wpa_supplicant( 1163): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1163): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1163): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_suppli,cant( 1163): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1163): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1163): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-59
I/wpa_supplicant( 1163): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1163): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1163): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-76
I/wpa_supplicant( 1163): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
D/wpa_supplicant( 1163): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=15 entropy=5
D/wpa_supplicant( 1163): Add randomness: count=16 entropy=6
D/wpa_supplicant( 1163): Add randomness: count=17 entropy=7
D/wpa_supplicant( 1163): Add randomness: count=18 entropy=8
D/wpa_supplicant( 1163): Add randomness: count=19 entropy=9
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1163): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): clear disabled list - type=1
I/wpa_supplicant( 1163): No suitable network found
W/wpa_supplicant( 1163): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1163): State: DISCONNECTED -> INACTIVE
D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/WifiNative-wlan0(  903): doBoolean: SET pno 1
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =INACTIVE
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): CTRL_IFACE SET 'pno'='1'
D/WifiP2pService(  903): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@432cae58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@432cae58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@432cae58 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1163): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1163): reply (778) for get BSS: id=1
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000105078999
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=5
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-59
I/wpa_supplicant( 1163): tsf=0000000585346894
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=6
I/wpa_supplicant( 1163): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-48
I/wpa_supplicant( 1163): tsf=0000000585346870
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1163): ssid=01ABC
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=7
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2427
I/wpa_supplicant( 1163): level=-73
I/wpa_supplicant( 1163): tsf=0000000585346909
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=8
I/wpa_supplicant( 1163): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-76
I/wpa_supplicant( 1163): tsf=0000000585346918
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1163): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=9
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-87
I/wpa_supplicant( 1163): tsf=0000000585346928
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ####
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 2412, timestamp: 105078999, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 5220, timestamp: 585346894, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -48, frequency: 2412, timestamp: 585346870, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 585346909, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 4: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -76, frequency: 2437, timestamp: 585346918, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 585346928, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 6 to mScanResults
D/BatSI   (  903): WIFI scan stopped for: 440a0300 uid:1000
,D/WifiStateMachine(  903): == (6) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 77 (NL80211_CMD_SCHED_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
D/wpa_supplicant( 1163): BSS: last_scan_res_used=1/32 last_scan_full=1
D/wpa_supplicant( 1163): Add randomness: count=20 entropy=10
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[1] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1163): WPS: AP[3] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 3
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 0
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): selected network = 1
D/wpa_supplicant( 1163): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8d404e8  current_ssid=0x0
D/wpa_supplicant( 1163): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1163): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1163): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1163): check if in concurrent case
I/wpa_supplicant( 1163): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1163): wpa_sup,plicant_associate, 1777
D/wpa_supplicant( 1163): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1163): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1163): RSN: PMKSA cache search - network_ctx=0xb8d404e8 try_opportunistic=0
D/wpa_supplicant( 1163): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1163): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1163): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1163): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1163): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1163): nl80211: Unsubscribe mgmt frames handle 0xb8d3f718 (mode change)
D/wpa_supplicant( 1163): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8d3f718
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8d3f718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1163):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1163):   * freq=2412
D/wpa_supplicant( 1163):   * Auth Type 0
D/wpa_supplicant( 1163):   * WPA Versions 0x2
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1163): nl80211: Connect request send successfully
D/wpa_supplicant( 1163): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =INACTIVE newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1163): reply (778) for get BSS: id=1
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-50
I/wpa_supplicant( 1163): tsf=0000000587348140
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=5
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-59
I/wpa_supplicant( 1163): tsf=0000000585346894
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=6
I/wpa_supplicant( 1163): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-48
I/wpa_supplicant( 1163): tsf=0000000585346870
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1163): ssid=01ABC
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=7
I/wpa_supplicant( 1163): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1163): freq=2427
I/wpa_supplicant( 1163): level=-73
I/wpa_supplicant( 1163): tsf=0000000585346909
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1163): ssid=Gonzos
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=8
I/wpa_supplicant( 1163): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-76
I/wpa_supplicant( 1163): tsf=0000000585346918
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1163): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=9
I/wpa_supplicant( 1163): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1163): freq=2437
I/wpa_supplicant( 1163): level=-87
I/wpa_supplicant( 1163): tsf=0000000585346928
I/wpa_supplicant( 1163): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=UPC4688432
I/wpa_supplicant( 1163): ####
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 587348140, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (6) end of scan result ==
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 5220, timestamp: 585346894, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -48, frequency: 2412, timestamp: 585346870, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 585346909, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 4: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -76, frequency: 2437, timestamp: 585346918, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 585346928, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 6 to mScanResults
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  903): getDiscoveryDongleList,
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1163): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1163): nl80211: Connect event
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1163): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1163): Add randomness: count=21 entropy=11
I/wpa_supplicant( 1163): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1163): TDLS: Remove peers on association
D/wpa_supplicant( 1163): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1163): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1163): EAPOL: enable timer tick
D/wpa_supplicant( 1163): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1163): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1163): Get randomness: len=32 entropy=12
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  903): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  903): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  903): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/wpa_supplicant( 1163): htc_wext_set_keepalive +
I/wpa_supplicant( 1163): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1163): getPrivFuncNum +	
I/wpa_supplicant( 1163): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive fnum = 0x8bf6
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
I/wpa_supplicant( 1163): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  903): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  903): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  903): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  903): Enter handleAssociatedWithEvent
D/WifiStateMachine(  903): Associated
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  903): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  903): Exit handleAssociatedWithEvent
D/Tethering(  903): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  903): BSSID was changed, update WiFi database
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  903): This record is existed, only update it...
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,I/wpa_supplicant( 1163): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8d3f9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1163):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1163): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6efdb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1163):    broadcast key
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1163): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1163): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1163): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1163): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1163): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1163): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1163): set send_ind_to_ndc = 0
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1163): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1163): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1163): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1163): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1163): EAPOL: SUPP_PAE entering state AUTHENTICATED
,D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1163): EAPOL authentication completed successfully
I/wpa_supplicant( 1163): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
D/Tethering(  903): interfaceStatusChanged wlan0, true
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  903): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  903): This record is existed, only update it...
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  903): Provision feature enable=false
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  903): mActiveDefaultNetwork: -1
,D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1869/10178)
D/WISPrService( 4461): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4461): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiNative-wlan0(  903): doBoolean: SET pno 0
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1163): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1163): nl80211: Event message available
,D/wpa_supplicant( 1163): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,D/WifiNative-wlan0(  903):    returned true
D/DhcpStateMachine(  903): [StoppedState] Start DHCP
,D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 0
D/WifiStateMachine(  903): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  903): acquireWL(42992938): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 903 1000 null
,D/WifiStateMachine(  903): handlePreDhcpSetup mBluetoothConnectionActive: false
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1163): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1163): Power_Mode_Type mode = 1
I/wpa_supplicant( 1163): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  903):    returned null
E/WifiStateMachine(  903): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  903):    returned null,
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41f43980 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41f43980 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  903): startScan Pid: 903 Uid 1000
,D/wpa_supplicant( 1163): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1163): EAPOL: disable timer tick
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1163): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  903): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  903): releaseWL(42992938): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=75 [4][3][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WIFI_ICON( 1112): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): gateway: /192.168.1.1
D/WifiNative-wlan0(  903): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1163): htc_wext_set_keepalive +
I/wpa_supplicant( 1163): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1163): getPrivFuncNum +	
I/wpa_supplicant( 1163): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1163): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1163): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1163): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  903): VerifyingLinkState enter
D/WifiStateMachine(  903): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiNative-wlan0(  903): doBoolean: SCAN TYPE=ONLY
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/WifiNative-wlan0(  903):    returned true
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiStateMachine(  903): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  903): VerifyingLinkState: enableIpv6
,D/BatSI   (  903): WIFI scan started for: 450a0300 uid:1000
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -48, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  903): WAN detection
V/NetworkPolicy(  903): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  903): Policy requires mobile/UNKNOWN teardown quickly
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  903): default: teardown()
D/MDST    (  903): default: setTeardownRequested(true)
D/MDST    (  903): default: setEnableApn apnType =default , enable=false
D/MDST    (  903): default: setTeardownRequested(true)
,D/ConnectivityService(  903): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,D/WISPrService( 4461): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1869/10178)
E/ConnectivityService(  903): Unexpected mtu value: android.net.wifi.WifiStateTracker@4275da60
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=false resetMask=0
,I/QuickSettingWifi( 1112): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  903): syncGetConfiguredNetworks
E/NetdConnector(  903): NDC Command {61 resolver setifdns wlan0  192.168.1.1} took too long (805ms)
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  903): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  903): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  903): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/WirelessDisplayService(  903): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  903): acquireWL(42a0cd80): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
D/ConnectivityService(  903): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4704/10078)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WirelessDisplayService(  903):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,D/PMS     (  903): acquireWL(42de2d70): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1217 10028 null
,D/PMS     (  903): releaseWL(42a0cd80): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(428ceb28): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1217 10028 null
I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  903): releaseWL(42de2d70): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
,I/CheckinService( 1217): Preparing to send checkin request
,I/EventLogService( 1217): Accumulating logs since 1450484643840
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 1217): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1217): Using GMS GoogleHttpClient
D/ConnectivityService(  903): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (1217/10028)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (1217/10028)
,W/GLSUser ( 1362): GoogleAccountDataService.getToken()
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PMS     (  903): releaseWL(43cebd60): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  903): NetTransition Wakelock for ConnectedState released by timeout
,D/DotMatrix( 1570): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1217): awaiting user notification for token
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{42262f28 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.google.android.gms 1 10 3 12
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (4536/10028)
,I/Adreno-EGL( 4536): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4536): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4536): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4536): Local Branch: 
I/Adreno-EGL( 4536): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4536): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4536):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4536): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4536): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4536): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4536): Local Branch: 
I/Adreno-EGL( 4536): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4536): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4536):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4536): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4536): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4536): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4536): Local Branch: 
I/Adreno-EGL( 4536): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4536): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4536):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: true
,W/Settings( 4536): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
D/CaptivePortalTracker(  903): NoActiveNetworkState
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,I/ConnectivityHelper( 1263): [onReceive] WIFI(1): CONNECTED
,V/Tethering(  903): bSetPropertyMultiRAB:false
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4704/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1404/10028)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1263/10075)
D/PMS     (  903): acquireWL(43b50b30): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (4623/10154)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1869/10178)
D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
I/acms    ( 1898): Checking Certificates
I/acms    ( 1898): Checking Developer Certificates
I/acms    ( 1898): Checking Application Certificates
I/NetworkMonitor( 4623): type=WIFI subType= reason=null isConnected=true
I/acms    ( 1898): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1898): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1898): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1898): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1898): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1898): Updating next query delay: 75600000
I/mlserverapp( 1898): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1898): cancelACMSProgrammedChecks
I/Tethering(  903): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  903): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  903): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  903): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  903): Found interface wlan0
,D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1898/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
D/PMS     (  903): acquireWL(4419e318): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  903): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
D/PMS     (  903): releaseWL(4419e318): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  903): releaseWL(43b50b30): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (2741/10021)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4652/10026)
,I/CheckinTask( 1217): Sending checkin request (8957 bytes)
D/libc    ( 1217): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1217): [NET] getaddrinfo-,err=8
D/libc    ( 1217): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1217): [NET] getaddrinfo-, 1
,D/libc    ( 1217): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8d48 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  903): acquireWL(433848b8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1217 10028 null
D/PMS     (  903): releaseWL(433848b8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1362): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/PMS     (  903): acquireWL(439655f0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1362 10028 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
D/libc    ( 1362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1362): [NET] getaddrinfo-,err=8
D/libc    ( 1362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1362): [NET] getaddrinfo-, 1
D/libc    ( 1362): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =cffb +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,D/AutoSetting( 1429): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4704): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/AutoSetting( 1429): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1429/10053)
D/AutoSetting( 1429): service - onStartCommand() screen is off, don't request location
,D/MobileConnectivityChangeReceiver( 4704): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1429/10053)
,D/AutoSetting( 1429): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1429): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4733/10151)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4107/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4107/10160)
,D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1869/10178)
,D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-59
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
D/wpa_supplicant( 1163): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=22 entropy=0
D/wpa_supplicant( 1163): Add randomness: count=23 entropy=1
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (238) for get BSS: id=1
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-50
I/wpa_supplicant( 1163): tsf=0000000592891457
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=5
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-59
I/wpa_supplicant( 1163): tsf=0000000592891471
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -50, 0
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiStateMachine(  903): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 592891457, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 5220, timestamp: 592891471, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 2 to mScanResults
V/ScoreHelper(  903): Only print Top 10 in ApScanList
V/ScoreHelper(  903):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-50], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  903):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-59], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  903):  + computeScore(NG700): 1
D/WifiStateMachine(  903): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (2) end of scan result ==
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/BatSI   (  903): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/WifiStateMachine(  903): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  903): acquireWL(42deb0f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42deb0f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1112): closing low battery warning: level=100
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8fac +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 28
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 32
,D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1217): [NET] getaddrinfo_proxy-, success
D/libc    ( 1362): [NET] getaddrinfo_proxy-, success
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  903): Find DNS Address www.htc.com/23.59.123.86
,D/PMS     (  903): releaseWL(439655f0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{44329230 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/libc    ( 1217): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1217): [NET] getaddrinfo-,err=8
D/libc    ( 1362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1362): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
,D/PMS     (  903): acquireWL(43280ca0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
,D/PMS     (  903): releaseWL(43280ca0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GCM     ( 1362): Connected
D/PMS     (  903): acquireWL(43757938): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1362 10028 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/PMS     (  903): acquireWL(43255558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1362/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
D/PMS     (  903): releaseWL(43255558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/PMS     (  903): releaseWL(43757938): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  903): acquireWL(43280a78): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1362 10028 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
,D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1362/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1362): Message class mpf
D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1362/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
,D/PMS     (  903): acquireWL(42ec5db0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
,D/PMS     (  903): releaseWL(43280a78): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  903): releaseWL(42ec5db0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (1217/10028)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=29 [47][14][0]
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (1217/10028)
,W/GLSUser ( 1362): GoogleAccountDataService.getToken()
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1570): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/CheckinRequestBuilder( 1217): awaiting user notification for token
,I/RemoteViews( 1112): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41fb4b58 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.google.android.gms 3 14 3 12
,I/CheckinTask( 1217): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1217): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1217/10028)
,D/PMS     (  903): releaseWL(428ceb28): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/GCM     ( 1362): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,E/ActivityThread( 1217): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@420d0b90 that was originally bound here
E/ActivityThread( 1217): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@420d0b90 that was originally bound here
E/ActivityThread( 1217): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1217): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1217): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1217): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1217): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1217): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1217): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1217): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1217): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1217): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1217): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1217): 	at bks.a(SourceFile:298)
E/ActivityThread( 1217): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1217): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1217): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1217): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1362): GCM config loaded
,D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  903): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  903): acquireWL(43755070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/BatteryService(  903): n_update end
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(43755070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  903): acquireWL(43fe2940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=616958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43fe2940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1237): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1237): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1237): sku_id=99
,D/ContactMessageStore( 1237): start background delete task...
,D/ContactMessageStore( 1237): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1237): size: 0 , 0
,D/ContactMessageStore( 1237): Background delete complete
,D/AutoSetting( 1429): service - has update message, not stop
,D/AutoSetting( 1429): service - mHandler: update timezone
,D/AutoSetting( 1501): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1501): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1501): service - onCreate()
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1501): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1501): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  903): batLight: Full, plugged
,D/DotMatrix( 1570): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1501): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1501): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1501): service - mHandler: update timezone
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1501): service - processTimeZoneID() system nitz: ,
,D/AutoSetting( 1501): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1501): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1501): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1570): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1112): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41e76598 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.htc.htclocationservice 3 7 3 11
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{43fc9400 u0 com.htc.htclocationservice/.AutoSettingService}
,D/AutoSetting( 1429): service - handleMessage() stop self
,D/AutoSetting( 1429): service - handleMessage() quit looper
,D/AutoSetting( 1429): service - onDestroy() END
,D/AutoSetting( 1501): service - handleMessage() stop self
,D/AutoSetting( 1501): service - onDestroy() END
,D/AutoSetting( 1501): service - handleMessage() quit looper
,D/PMS     (  903): acquireWL(42de5e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(42de5e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43e080b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10028}
,V/AlarmManager(  903): sending alarm PendingIntent{43f628b0: PendingIntentRecord{42867b48 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450484673496, Int=1800000
,D/PMS     (  903): acquireWL(43938c50): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1217 10028 null
,I/ActivityManager(  903): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4947 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  903): sending alarm PendingIntent{42910328: PendingIntentRecord{428ecbf0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450484714162, Int=10800000
,D/PMS     (  903): acquireWL(426bf2a8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1217 10028 null
,D/PMS     (  903): releaseWL(43938c50): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,V/AlarmManager(  903): sending alarm PendingIntent{433f4590: PendingIntentRecord{427baad8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450485166855, Int=0
,I/EventLogService( 1217): Aggregate from 1450485094789 (log), 1450482873353 (data)
D/PMS     (  903): releaseWL(43e080b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,W/GLSUser ( 1362): GoogleAccountDataService.getToken()
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.aurora (4947/10047)
,D/PMS     (  903): releaseWL(426bf2a8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1362): GoogleAccountDataService.getToken()
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4071): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4071): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1362): GoogleAccountDataService.getToken()
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1362): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1362): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4071): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4071): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4071): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/Process (  903): killProcessQuiet, pid=4390
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4390:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4390
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  903): killProcessQuiet, pid=4033
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4033:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4033
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(43a5eb98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43a5eb98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43cf22f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=676958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43cf22f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43281950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10073}
,V/AlarmManager(  903): sending alarm PendingIntent{43c61018: PendingIntentRecord{43acf930 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450485182089, Int=0
,D/PMS     (  903): releaseWL(43281950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4071): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  903): acquireWL(43cadf60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43cadf60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  903): updateBatteryInfo
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43c7f648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=736958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43c7f648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(426c26c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(426c26c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
,D/PMS     (  903): acquireWL(437cace8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{42130e10: PendingIntentRecord{427a4460 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=779873, Int=0
,D/PMS     (  903): releaseWL(437cace8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  903): Done.
,D/ConnectivityService(  903): Setting timer for 720seconds
,D/PMS     (  903): acquireWL(429a7118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(429a7118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42ed3720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=796958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42ed3720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43b43b78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/PMS     (  903): releaseWL(43b43b78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42f67a48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=856958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42f67a48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43adda58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43adda58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/ContextImpl( 4788): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4461): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4461): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4461): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4461): Cust_ConnectToPC   : spcsc>false
D/        ( 4461): Cust_ConnectToPC   : IPT>true
D/        ( 4461): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4461): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4461): Index of the first 1 = 3
W/Settings( 4461): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4461): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4461): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4461): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
W/ContextImpl( 4461): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
D/SmartNS_Utility( 4461): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  903): acquireWL(42aa04c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=916958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42aa04c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42f03ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(42f03ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43c1d068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(43c1d068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42dede50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=976959, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42dede50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(439bc370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(439bc370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42ec78a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{42896030: PendingIntentRecord{428ecff0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450485434683, Int=900000
,V/AlarmManager(  903): sending alarm PendingIntent{4290ab50: PendingIntentRecord{428ffee0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450485510657, Int=0
,W/ContextImpl( 4788): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4788): call getInstance()
,D/SmartSyncUtils( 4788): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4788): MY_DEBUG = false
,D/PMS     (  903): releaseWL(42ec78a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43c951c0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4788 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4788): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4788): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 7, bNormalRange = true
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/SmartSyncScreenOnOffTimeReceiver( 4788): [updateNmRange] new USERNIGHT_TIMESTART = 1, new USERNIGHT_TIMEEND = 7
W/ContextImpl( 4788): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.updateNmRange:2650 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.SettingPowerModeAlarm:972 
,D/SmartSyncScreenOnOffTimeReceiver( 4788): AlarmOnTime = -1
,I/FeedHostManager( 1263): onReceive() -- Intent { act=com.htc.powersaver.SMARTSYNC_SLEEPMODE_TIME_UPDATE flg=0x10 }
,D/SmartSyncScreenOnOffTimeReceiver( 4788): SettingOnTime = 1450504800000, randomSettingOnTime = 1450501557000
,D/PMS     (  903): acquireWL(42c25518): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1263 10075 null
,I/FeedHostManager( 1263): NightMode begin at 0, end at 7
D/SmartSyncScreenOnOffTimeReceiver( 4788): SettingOffTime = 1450569600000, randomSettingOffTime = 1450575998000
,D/SmartSyncScreenOnOffTimeReceiver( 4788): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 4788): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4788): bNightModeTurnOffOnce = false
,I/FeedHostManager( 1263): scheduleNextNightModeAlarm - today's NightMode - CurrentTime: 1450485510782, BeginTime: 1450479600000, EndTime: 1450504800000
D/PMS     (  903): acquireWL(4298ba98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{43d4e340: PendingIntentRecord{4293a1e8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1450485510803, Int=0
V/AlarmManager(  903): sending alarm PendingIntent{43771fb8: PendingIntentRecord{4295d5a8 com.htc.launcher broadcastIntent}}, i=com.htc.laucher.NIGHT_MODE_BEGIN, t=0, cnt=1, w=1450479600000, Int=0
D/PMS     (  903): releaseWL(42c25518): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
D/PMS     (  903): releaseWL(43c951c0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/ContextImpl( 4788): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/FeedHostManager( 1263): onReceive() -- Intent { act=com.htc.laucher.NIGHT_MODE_BEGIN flg=0x14 (has extras) }
D/SmartSyncUtils( 4788): getMobilePolicyEnabled, result = true
,D/SmartSyncDataLinkTurnOffService( 4788): turnOffMobile bPolicyEnabled = true
,D/WifiStateMachine(  903): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartSyncUtils( 4788): isWifiHotSpotEnabled = false
D/PMS     (  903): acquireWL(44260850): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1263 10075 null
D/PMS     (  903): releaseWL(44260850): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
,D/PMS     (  903): releaseWL(4298ba98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10075}
D/SmartSyncDataLinkTurnOffService( 4788): turnOffMobile bCheckMobileData = false
D/LocationManagerService(  903): getProviders()=[gps, network]
D/LocationManagerService(  903): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
D/LocationManagerService(  903): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/SmartSyncDataLinkTurnOffService( 4788): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
D/SmartSyncUtils( 4788): isCharging status = 5
,D/SmartSyncDataLinkTurnOffService( 4788): turnOffWifi ui setting = true
,D/WifiStateMachine(  903): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartSyncUtils( 4788): isWifiHotSpotEnabled = false
,D/SmartSyncUtils( 4788): isWifiCallingOn, bOn = false
,D/SmartSyncDataLinkTurnOffService( 4788): turnOffWifi bCheckWifiData = true
,D/SmartSyncDataLinkTurnOffService( 4788): turnOffWifi bWifiConnected = true
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4788/1000)
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(426a5910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,I/BatteryService(  903): n_update end
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): releaseWL(426a5910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4327d460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1036959, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4327d460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43c9e510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): releaseWL(43c9e510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43660d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{420be448: PendingIntentRecord{42805be8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1060964, Int=0
,D/PMS     (  903): acquireWL(43748168): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
D/PMS     (  903): releaseWL(43660d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42426c68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(43748168): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  903): releaseWL(42426c68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  903): acquireWL(42fbf298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42fbf298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(426a9bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1096958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(426a9bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42861ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(42861ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43ca8860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(43ca8860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
,D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42940bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1156958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42940bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4283d8a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PowerUI ( 1112): closing low battery warning: level=100
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(4283d8a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  903): updateBatteryInfo
D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4270bcc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4343e328: PendingIntentRecord{4293dba0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_WIFI_RETRY, t=0, cnt=1, w=1450485690859, Int=0
,W/ContextImpl( 4788): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  903): releaseWL(4270bcc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncDataLinkTurnOffService( 4788): turnOffWifi ui setting = true
,D/WifiStateMachine(  903): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartSyncUtils( 4788): isWifiHotSpotEnabled = false
,D/SmartSyncUtils( 4788): isWifiCallingOn, bOn = false
D/SmartSyncDataLinkTurnOffService( 4788): turnOffWifi bCheckWifiData = false
,D/SmartSyncDataLinkTurnOffService( 4788): turnOffWifi bWifiConnected = true
D/LocationManagerService(  903): getProviders()=[gps, network]
,D/LocationManagerService(  903): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  903): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4788/1000),
D/SmartSyncDataLinkTurnOffService( 4788): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
D/SmartSyncUtils( 4788): isCharging status = 5
,D/PMS     (  903): acquireWL(429ac578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  903): releaseWL(429ac578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus,
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  903): acquireWL(42ed6e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1216958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42ed6e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43bce818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43bce818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42ab4fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42ab4fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,D/PowerUI ( 1112): closing low battery warning: level=100
,D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43a5fa90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1276958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43a5fa90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(428aed20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(428aed20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43c7ad40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43c7ad40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42894ee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1336958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42894ee8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4430c710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4430c710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43c96a48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43c96a48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42ec99d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1396958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42ec99d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43d4a0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43d4a0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43c60fd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43c60fd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42afaa10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1456958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42afaa10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43d25a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(43d25a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43fe6d50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43fe6d50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(435a1a78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1516958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(435a1a78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4293d8b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,D/PMS     (  903): releaseWL(4293d8b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43addae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43addae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42f41bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1576958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42f41bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(427a5c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(427a5c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,D/PowerUI ( 1112): closing low battery warning: level=100
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43ca7a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43ca7a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(4408a178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1636958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4408a178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4368abc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(4368abc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1112): closing low battery warning: level=100
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43ce5570): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43ce5570): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43d4fad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1696958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43d4fad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(429e8738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(429e8738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42fb8c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(42fb8c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43f68098): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1756958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43f68098): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43c9be38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(43c9be38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(42f9fd08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/PMS     (  903): releaseWL(42f9fd08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  903): acquireWL(43a75798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1816958, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  903): Prepared write state in 39ms
,D/PMS     (  903): releaseWL(43a75798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  903): Pruning old procstats: /data/system/procstats/state-2015-12-18-12-57-06.bin
,D/PMS     (  903): acquireWL(43a5cff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  903): sending alarm PendingIntent{42130e10: PendingIntentRecord{427a4460 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1499888, Int=0
,V/AlarmManager(  903): sending alarm PendingIntent{429ae630: PendingIntentRecord{42862a90 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1500197, Int=0
,V/AlarmManager(  903): sending alarm PendingIntent{426fdcb8: PendingIntentRecord{42868fd8 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820401, Int=1800000
,V/AlarmManager(  903): sending alarm PendingIntent{42896030: PendingIntentRecord{428ecff0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450486334683, Int=900000
,D/PMS     (  903): acquireWL(43a3c598): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1362 10028 null
,D/PMS     (  903): releaseWL(43a3c598): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
D/ConnectivityService(  903): Done.
D/ConnectivityService(  903): Setting timer for 720seconds
,D/PMS     (  903): acquireWL(42f1d390): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
,D/PMS     (  903): acquireWL(438183a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
,D/PMS     (  903): releaseWL(42f1d390): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  903): releaseWL(438183a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/ContextImpl( 4788): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  903): releaseWL(43a5cff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(43700780): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1362 10028 null
,D/GCM     ( 1362): Message class mow
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1362/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1362/10028)
,D/PMS     (  903): acquireWL(4268cef0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1362 10028 null
,D/PMS     (  903): releaseWL(43700780): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  903): releaseWL(4268cef0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=10 [89][9][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(43c628c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): closing low battery warning: level=100
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(43c628c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42961338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e64890: PendingIntentRecord{423be908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1876958, Int=0
,D/Process (  903): killProcessQuiet, pid=4217
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  903): Killing 4217:com.google.android.configupdater/u0a16 (adj 15): empty for 1804s
I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42961338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  903): Recipient 4217
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(42758378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42758378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1570): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 5008): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5008): ====startRecUseTime====
D/htc.customization.log.level( 5008):  is 
W/CustomizationLogLevel( 5008): Level value is invalid, use default level 2
D/CustomizationManager( 5008):  Read ACC file spent 0.110 (s)
D/CIDMapFileReader( 5008): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5008): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5008): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5008): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5008): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5008): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5008): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5008): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5008): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5008): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5008): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5008): Parsing tag category name = system
I/CustomizationCIDLoader( 5008): Parsing tag category name = application
I/CustomizationCIDLoader( 5008): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5008): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5008): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5008): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5008): Parsing tag category name = Settings
D/CustomizationManager( 5008):  Read CID file spent 0.166 (s)
D/CustomizationManager( 5008):  All configurations done spent 0.167 (s)
W/HtcNativeFlag( 5008): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5008): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5008): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5008): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  903): deletePackageAsUser: pkg=com.test.thalitest, pid=5008, uid=2000 user=0
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  903): killProcessQuiet, pid=4522
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  903): Killing 4522:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1814s
I/ActivityManager(  903): Recipient 4522
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  903): Skipping PackageSetting{4259c620 com.example.hello/10356} due to missing metadata
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
I/acms    ( 1898): Unregistering com.test.thalitest
E/acms    ( 1898): Could not unregister removed application com.test.thalitest
D/DotMatrix( 1570): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
D/DotMatrix( 1570): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
D/DotMatrix( 1570): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1404): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
D/PMS     (  903): acquireWL(43d28358): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1404 10028 null
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  903): releaseWL(43d28358): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/Prism.ItemManager( 1263): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1263): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/Launcher( 1263): Deferring update until onResume
D/Launcher( 1263): waitUntilResume // bindAppsRemoved
I/InputMethodManagerService(  903): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
D/VoicemailCleanupService( 1293): Cleaning up data for package: com.test.thalitest
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
D/PackageBroadcastService( 1217): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/ActivityManager(  903): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=5023 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
E/ExternalAccountType( 1327): Unsupported attribute readOnly
W/SystemReader( 1251): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
D/PhoneApp( 1237): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 5023): install
I/ActivityManager(  903): Delaying start of: ServiceRecord{43a6c670 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 5023): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PeopleContactsSync( 1217): CP2 sync disabled
I/MultiDex( 5023): loading existing secondary dex files
I/MultiDex( 5023): load found 1 secondary dex files
I/MultiDex( 5023): install done
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1217, uid=10028, userID:0
D/PMS     (  903): acquireWL(42722260): PARTIAL_WAKE_LOCK  Icing 0x1 1217 10028 null
I/Icing   ( 1217): doRemovePackageData com.test.thalitest
D/PMS     (  903): releaseWL(42722260): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  903): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=5041 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 5023): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  903): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 5041): install
I/MultiDex( 5041): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 5041): loading existing secondary dex files
I/MultiDex( 5041): load found 1 secondary dex files
I/MultiDex( 5041): install done
I/ActivityManager(  903): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1429): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1429): handle notify Blinkfeed plugin client changed
I/ProviderInstaller( 5041): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  903): Resuming delayed broadcast
D/Prism.PackageStateRece_( 1263): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2874): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5061 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 5023): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 5023): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5023): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5023): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5023): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 5023): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 5023): 	at ctn.run(SourceFile:985)
W/dalvikvm( 5023): threadid=12: thread exiting with uncaught exception (group=0x41a3ae30)
E/ActivityManager(  903): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 5023): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5023): Process: com.google.android.gms.drive, PID: 5023
E/AndroidRuntime( 5023): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5023): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5023): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5023): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 5023): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 5023): 	at ctn.run(SourceFile:985)
D/Process ( 5023): killProcess, pid=5023
D/Process ( 5023): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/SQLiteLog( 2874): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2874): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5cacc8b8
W/dalvikvm( 2874): threadid=14: thread exiting with uncaught exception (group=0x41a3ae30)
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop148.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
E/AndroidRuntime( 2874): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2874): Process: com.google.android.googlequicksearchbox:search, PID: 2874
E/AndroidRuntime( 2874): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2874): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2874): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2874): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2874): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2874): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2874): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2874): 	at cid.d(PG:186)
E/AndroidRuntime( 2874): 	at clo.g(PG:594)
E/AndroidRuntime( 2874): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2874): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2874): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2874): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2874): 	at clr.tL(PG:827)
E/AndroidRuntime( 2874): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2874): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2874): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2874): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2874): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2874): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  903): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2874): killProcess, pid=2874
D/Process ( 2874): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop149.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
I/ActivityManager(  903): Recipient 5023
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  903): Client connection lost with reason: 4
I/ActivityManager(  903): Process com.google.android.gms.drive (pid 5023) has died.
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2874
D/MediaRouterService(  903): Client com.google.android.googlequicksearchbox (pid 2874): Died!
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  903): Process com.google.android.googlequicksearchbox:search (pid 2874) has died.
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
E/SQLiteDatabase( 5061): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5061): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5061): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5061): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5061): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5061): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5061): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5061): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5061): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5061): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5061): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5061): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5061): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5061): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5061): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5061): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5061): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5061): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5061): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5061): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5061): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5061): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5061): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5061): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5061): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5061): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5061): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5061): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5061): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5061): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5061): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5061): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5061): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5061): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5061): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5061): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5061): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5061): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5061): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5061): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5061): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5061): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5061): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5061): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5061): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5061): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5061): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5061): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5061): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5061): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5061): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5061): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5061): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5061): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5061): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5061): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5061): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5061): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5061): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5061): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5061): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5061): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5061): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5061): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5061): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5061): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5061): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5061): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5061): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5061): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5061): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5061): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5061): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5061): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5061): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5061): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5061): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5061): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5061): threadid=11: thread exiting with uncaught exception (group=0x41a3ae30)
E/ActivityManager(  903): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 5061): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5061): Process: com.google.android.apps.docs, PID: 5061
E/AndroidRuntime( 5061): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5061): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5061): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5061): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5061): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5061): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5061): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5061): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5061): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5061): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5061): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5061): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5061): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5061): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5061): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5061): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5061): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5061): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5061): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop150.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
D/Process ( 5061): killProcess, pid=5061
D/Process ( 5061): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  903): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5079 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  903): Recipient 5061
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageManager(  903): Unable to load service info ResolveInfo{43c9e9c0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  903): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  903): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  903): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  903): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  903): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  903): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  903): Process com.google.android.apps.docs (pid 5061) has died.
W/ContextImpl( 5079): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  903): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5092 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 5079): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5079): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5079): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5079): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5079): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5079): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5079): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5079): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5079): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5079): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5079): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5079): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5079): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5079): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5079): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5079): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5079): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5079): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5079): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5079): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5079): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5079): threadid=10: thread exiting with uncaught exception (group=0x41a3ae30)
E/AndroidRuntime( 5079): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5079): Process: com.android.keychain, PID: 5079
E/AndroidRuntime( 5079): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5079): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5079): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5079): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5079): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5079): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5079): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5079): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5079): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5079): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5079): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5079): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5079): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5079): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5079): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5079): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5079): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5079): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5079): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5079): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  903): App crashed! Process: com.android.keychain
D/ErrorReport(  903): HtcErrorReportManager Begin---add error logs to dropbox
I/Prism.ItemManager( 1263): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1263): loadItems() com.htc.launcher.pageview.WidgetManager@41efdd30 +
I/Prism.WidgetManager( 1263): onLoadItems() +
D/AppTag  ( 5092): getInstance(Context context)
D/AppTag  ( 5092): getInstance(Context context)
D/AppTag  ( 5092): onCreate()
I/ActivityManager(  903): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  903): acquireWL(428d76f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4107 10160 null
D/Process ( 5079): killProcess, pid=5079
D/Process ( 5079): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/PMS     (  903): releaseWL(428d76f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  903): Resuming delayed broadcast
E/ErrorReport(  903): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  903): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450486415623.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  903): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  903): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  903): 	... 4 more
I/ActivityManager(  903): Recipient 5079
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5110 uid=10098 gids={50098, 3003, 5012}
I/ActivityManager(  903): Process com.android.keychain (pid 5079) has died.
W/ActivityManager(  903): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10260ms
I/DeviceManagement( 5110): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5110 dbg=false s=true
I/DeviceManagement( 5110): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5110): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5110): WorkflowService: Starting workflow service
I/DeviceManagement( 5110): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41e97d68] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5110): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5110): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5110): PackageUpdateWorkflow: ==================================================

```
